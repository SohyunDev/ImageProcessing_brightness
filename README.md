# ImageProcessing
Making Brightnessfunction with CxImage<br/>
2016. 2nd semester Practice (Image Processing)<br/>
Making Image brighter or darker<br/>

Color Data Structure<br/>
public:<br/>
>RGBQUAD m_color;<br/>
typedef struct tagRGBQUAD {<br/>
>BYTE rgbBlue;<br/>
>BYTE rgbGreen;<br/>
>BYTE rgbRed;<br/>
>BYTE rgbReserved;<br/>
} RGBQUAD;<br/>

Exception Handling<br/>
 - Range of RGB value : 0~255 (each value)<br/>
 - avoid overflow & underflow<br/>
 
