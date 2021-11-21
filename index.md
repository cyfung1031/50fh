# 50fh


## CG01 - 三角形四心
### CG01A - 93 BYTES - CMPLX; 重心、垂心、外心及內心(II)

http://webcal.freehostia.com/casio.fx-50FH/four_centre_2.htm

?→A: ?→B: ?→C: A + B + C→M: M÷3◢

(B - C) ÷( A - C→D: C-i (A - B) tan(arg(iD M-◢

. 5M◢ Abs(B - C) + Abs(A - C) - Abs(A - B:

Ans - i Ans tan( .5arg(D: C + Ans ( .5∠ arg(B - C 　

### CG01B - 135 BYTES - CMPLX; 三角形重心、垂心、內心、外心及三點求圓 

?→A: ?→B: ?→C: A + B + C→M: M÷3◢

(B - C) ÷( A - C→D: C-i (A - B) tan(arg(iD M-◢

.5( Abs(B - C) + Abs(A - C) - Abs(A - B→Y:

1 - i tan( .5arg(D: C + Ans Y∠ arg(B - C →X◢

Y Abs( tan( .5arg(D →Y: .5M M-◢ Abs(M-B→D:

?→M: ?→D: -2M◢ Abs(M)²-D²

### CG01B - Example
![image](https://user-images.githubusercontent.com/44498510/142735971-267da7fb-e114-46ff-a900-deeeec3dc822.png)

![image](https://user-images.githubusercontent.com/44498510/142735994-14e34bf1-4988-4020-b283-fc1c34f23a77.png)

- INPUTS: 20-120i, 40+20i, 100+40i
- OUTPUTS: 53.3-20i (形) , -40+60i (垂), 58.8+4.29i (內), 100-60i (外)
- M=100-60i; D=100; -200+120i, 3600
- M=X=58.8+4.29i; D=Y=20.86; -117.6-8.58i, 3043.7

## G01 - 解三角形(II)

### G01 - 197 BYTES

http://webcal.freehostia.com/casio.fx-50FH/solve_triangle2.htm

While 1: ?→A: ?→B: ?→C: 0>AB => Goto 0: B→X: - sin(C) ÷ sin(A→B:

0>A => cos⁻¹( (A²+X²-C²)÷ ( 2AX→B: X→C: Lbl 0: 0>C→D: Abs(A◢

Abs(B◢ 0>A => Break: D => πr - A - sin⁻¹( C⁻¹ Bsin(A→C: C◢

Pol( B tan(90° - A - C , -B ) sin(A◢ Y◢ X sin(C◢ - . 5AnsBsin(A◢

YD - A→C: Ans>0 => Goto 0: WhileEnd : cos⁻¹( D => Asin(B+C) ÷ sin(C→C:

-C◢ Pol(Ans + Acos(B , -Asin(B: Y◢ X◢ π<sup>r</sup> - B - Y◢ . 5ACsin(B

## A01 - 一元三次方程


### A01A - 126 BYTES - COMP; 實數系數; 實數根
http://webcal.freehostia.com/casio.fx-50FH/cubic2.htm (2A)

?→A: ?→B: ?→C: ?→M: - B┘(3A→B: BC M+:

B³ - M┘(2A→M: B² - C┘(3A→C: M² - C³:

If Ans>0: Then √( Ans M+: B + ³√( M ) + ³√( M - 2Ans◢ Lbl IfEnd:

2√( C→C: C => 3⁻¹ cos⁻¹( 8M÷C³→M: B + C cos(M◢

B - C cos( M + 60°◢ B - C cos( M - 60°

### A01B - 130 BYTES - COMP; 實數系數; 實數根
http://webcal.freehostia.com/casio.fx-50FH/cubic1.htm (1B)

?→A: ?→B: ?→C: ?→M: - B┘(3A→B: BCM+: C┘A→C:

B³ - M┘(2A→M: B² - C┘3→D: M² - Ans³:

If 0>Ans: Then 2 √( D ) cos( 3⁻¹ cos⁻¹( M÷√( D³: Else √( Ans M+:

³√(M )+ ³√( M - 2 Ans: IfEnd: Ans + B→A◢ 3B - Ans→M:

M┘2 + √(AM - C + M²┘4 M- →B◢ M

### A01C - 123 bytes - CMPLX; 實數系數; 複數根
http://webcal.freehostia.com/casio.fx-50FH/cubic1.htm (1C)

?→A: ?→B: ?→C: ?→D:

9A(BC - 3AD)┘2 - B³→M: √( M² + ( 3AC - B²)³ M+:

If Ans=Conig( Ans: Then ³√( M) + ³√( M - 2Ans:

Else 2 ³√(Abs( M ) ) cos( 3⁻¹arg( M: IfEnd:

(Ans - B)┘(3A◢ - B┘A - Ans→M: M┘2:

Ans + √(- 3 Ans² - BM┘A - C┘A M-◢ M

### A01D - 126 BYTES - CMPLX; 實數系數; 複數根
http://webcal.freehostia.com/casio.fx-50FH/cubic1.htm (1A)

?→A: ?→B: - B┘(3A→B: ?→C: C┘A→C: ?→M:

B³ - BAns┘2 - M┘(2A→M: √( ( C┘3 - B²)³ + Ans² M+:

If Ans=Conig( Ans: Then ³√( M) + ³√( M - 2Ans:

Else 2 ³√(Abs( M ) ) cos ( 3⁻¹arg( M: IfEnd: Ans + B→A◢

3B - Ans→M: M┘2 + √(AM - C + M²┘4 M- →B◢ M

### A01E - 119 BYTES - CMPLX; 實數系數; 複數根

http://webcal.freehostia.com/casio.fx-50FH/cubic4.htm (3A)

?→A: ?→B: ?→C: ?→D:

B³ - 9┘2A( BC - 3DA→D: B² - 3AC→C:  √( D² - C³:

Ans - D - 2Ans(Ans=D→D: ³√( Abs(Ans => Ans∠(3⁻¹ arg(D) + 5!° ( π<sup>r</sup> = arg( D→D:

While 1: Abs( D => D + C┘D: (Ans - B)┘(3A◢ 1∠5!°D→D: WhileEnd

### A01F - 121 BYTES - CMPLX; 複數系數; 複數根

http://webcal.freehostia.com/casio.fx-50FH/cubic4.htm (3B)

?→A: ?→B: ?→C: ?→D:

B³ - 9┘2A( BC - 3DA→D: B² - 3AC→C: 

√( Abs( D² - C³ => Ans∠( . 5 arg(D² - C³: Ans - D - 2Ans(Ans=D→D: 

³√( Abs(Ans => Ans∠(3⁻¹ arg(D→D:

While 1: Abs( D => D + C┘D: (Ans - B)┘(3A◢ 1∠5!°D→D: WhileEnd


## Symbols
https://www.piliapp.com/symbol/subscript-superscript/
