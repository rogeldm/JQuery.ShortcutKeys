# JQuery.ShortcutKeys
Add keyboard shortcuts to any element in your page easy

To assign a shortcut to an element you should only use the <b>setShortcutKey()</b> function, this function has the following parameters:

<table>
  <tr>
    <td><b>mod</b></td>
    <td>Defines the modifier key, in case a combination is not used, the value <b>NULL</b> is used as a parameter</td>
  </tr>
  <tr>
    <td><b>key</b></td>
    <td>Defines the key to be used for the shortcut</td>
  </tr>
  <tr>
    <td><b>func</b></td>
    <td>Defines the function that will be assigned to the shortcut</td>
  </tr>
</table>

<br>
The following shows how the shortcut method, defined with the key combination <b>ALT + RETURN</b>, would be set in the <b>#example</b> element:

```javascript
	$("#example").setShortcutKey(
		ALT ,
		RETURN ,
		function() {
			alert("Hello world!");
		}
	);
``` 
  
 

You can also set the key code as shown below and the result will remain the same:


```javascript
	$("#example").setShortcutKey(
		18 ,
		13 ,
		function() {
			alert("Hello world!");
		}
	);
``` 

<br>
<b>CONSTANTS</b>

<table>
  <tr>
    <th>Constant</th>
    <th>Key Code</th>
    <th>Key Name</th>
  </tr>
  <tr>
    <td>BACK_SPACE</td>
    <td>8</td>
    <td>BACKSPACE</td>
  </tr>
  <tr>
    <td>TAB</td>
    <td>9</td>
    <td>TAB</td>
  </tr>
  <tr>
    <td>RETURN</td>
    <td>13</td>
    <td>ENTER</td>
  </tr>
  <tr>
    <td>SHIFT</td>
    <td>16</td>
    <td>SHIFT</td>
  </tr>
  <tr>
    <td>CONTROL</td>
    <td>17</td>
    <td>CTRL</td>
  </tr>
  <tr>
    <td>ALT</td>
    <td>18</td>
    <td>ALT</td>
  </tr>
  <tr>
    <td>PAUSE</td>
    <td>19</td>
    <td>PAUSE/BREAK</td>
  </tr>
  <tr>
    <td>CAPS_LOCK</td>
    <td>20</td>
    <td>CAPS LOCK</td>
  </tr>
  <tr>
    <td>ESCAPE</td>
    <td>27</td>
    <td>ESCAPE</td>
  </tr>
  <tr>
    <td>PAGE_UP</td>
    <td>33</td>
    <td>PAGE UP</td>
  </tr>
  <tr>
    <td>PAGE_DOWN</td>
    <td>34</td>
    <td>PAGE DOWN</td>
  </tr>
  <tr>
    <td>END</td>
    <td>35</td>
    <td>END</td>
  </tr>
  <tr>
    <td>HOME</td>
    <td>36</td>
    <td>HOME</td>
  </tr>
  <tr>
    <td>LEFT</td>
    <td>37</td>
    <td>LEFT ARROW</td>
  </tr>
  <tr>
    <td>UP</td>
    <td>38</td>
    <td>UP ARROW</td>
  </tr>
  <tr>
    <td>RIGHT</td>
    <td>39</td>
    <td>RIGHT ARROW</td>
  </tr>
  <tr>
    <td>DOWN</td>
    <td>40</td>
    <td>DOWN ARROW</td>
  </tr>
  <tr>
    <td>INSERT</td>
    <td>45</td>
    <td>INSERT</td>
  </tr>
  <tr>
    <td>DELETE</td>
    <td>46</td>
    <td>DELETE</td>
  </tr>
  <tr>
    <td>N0</td>
    <td>48</td>
    <td>0</td>
  </tr>
  <tr>
    <td>N1</td>
    <td>49</td>
    <td>1</td>
  </tr>
  <tr>
    <td>N2</td>
    <td>50</td>
    <td>2</td>
  </tr>
  <tr>
    <td>N3</td>
    <td>51</td>
    <td>3</td>
  </tr>
  <tr>
    <td>N4</td>
    <td>52</td>
    <td>4</td>
  </tr>
  <tr>
    <td>N5</td>
    <td>53</td>
    <td>5</td>
  </tr>
  <tr>
    <td>N6</td>
    <td>54</td>
    <td>6</td>
  </tr>
  <tr>
    <td>N7</td>
    <td>55</td>
    <td>7</td>
  </tr>
  <tr>
    <td>N8</td>
    <td>56</td>
    <td>8</td>
  </tr>
  <tr>
    <td>N9</td>
    <td>57</td>
    <td>9</td>
  </tr>
  <tr>
    <td>A</td>
    <td>65</td>
    <td>A</td>
  </tr>
  <tr>
    <td>B</td>
    <td>66</td>
    <td>B</td>
  </tr>
  <tr>
    <td>C</td>
    <td>67</td>
    <td>C</td>
  </tr>
  <tr>
    <td>D</td>
    <td>68</td>
    <td>D</td>
  </tr>
  <tr>
    <td>E</td>
    <td>69</td>
    <td>E</td>
  </tr>
  <tr>
    <td>F</td>
    <td>70</td>
    <td>F</td>
  </tr>
  <tr>
    <td>G</td>
    <td>71</td>
    <td>G</td>
  </tr>
  <tr>
    <td>H</td>
    <td>72</td>
    <td>H</td>
  </tr>
  <tr>
    <td>I</td>
    <td>73</td>
    <td>I</td>
  </tr>
  <tr>
    <td>J</td>
    <td>74</td>
    <td>J</td>
  </tr>
  <tr>
    <td>K</td>
    <td>75</td>
    <td>K</td>
  </tr>
  <tr>
    <td>L</td>
    <td>76</td>
    <td>L</td>
  </tr>
  <tr>
    <td>M</td>
    <td>77</td>
    <td>M</td>
  </tr>
  <tr>
    <td>N</td>
    <td>78</td>
    <td>N</td>
  </tr>
  <tr>
    <td>O</td>
    <td>79</td>
    <td>O</td>
  </tr>
  <tr>
    <td>P</td>
    <td>80</td>
    <td>P</td>
  </tr>
  <tr>
    <td>Q</td>
    <td>81</td>
    <td>Q</td>
  </tr>
  <tr>
    <td>R</td>
    <td>82</td>
    <td>R</td>
  </tr>
  <tr>
    <td>S</td>
    <td>83</td>
    <td>S</td>
  </tr>
  <tr>
    <td>T</td>
    <td>84</td>
    <td>T</td>
  </tr>
  <tr>
    <td>U</td>
    <td>85</td>
    <td>U</td>
  </tr>
  <tr>
    <td>V</td>
    <td>86</td>
    <td>V</td>
  </tr>
  <tr>
    <td>W</td>
    <td>87</td>
    <td>W</td>
  </tr>
  <tr>
    <td>X</td>
    <td>88</td>
    <td>X</td>
  </tr>
  <tr>
    <td>Y</td>
    <td>89</td>
    <td>Y</td>
  </tr>
  <tr>
    <td>Z</td>
    <td>90</td>
    <td>Z</td>
  </tr>
  <tr>
    <td>WIN</td>
    <td>91</td>
    <td>LEFT WINDOW KEY</td>
  </tr>
  <tr>
    <td>WIN</td>
    <td>92</td>
    <td>RIGHT WINDOW KEY</td>
  </tr>
  <tr>
    <td>CONTEXT_MENU</td>
    <td>93</td>
    <td>SELECT KEY</td>
  </tr>
  <tr>
    <td>NUMPAD0</td>
    <td>96</td>
    <td>NUMPAD 0</td>
  </tr>
  <tr>
    <td>NUMPAD1</td>
    <td>97</td>
    <td>NUMPAD 1</td>
  </tr>
  <tr>
    <td>NUMPAD2</td>
    <td>98</td>
    <td>NUMPAD 2</td>
  </tr>
  <tr>
    <td>NUMPAD3</td>
    <td>99</td>
    <td>NUMPAD 3</td>
  </tr>
  <tr>
    <td>NUMPAD4</td>
    <td>100</td>
    <td>NUMPAD 4</td>
  </tr>
  <tr>
    <td>NUMPAD5</td>
    <td>101</td>
    <td>NUMPAD 5</td>
  </tr>
  <tr>
    <td>NUMPAD6</td>
    <td>102</td>
    <td>NUMPAD 6</td>
  </tr>
  <tr>
    <td>NUMPAD7</td>
    <td>103</td>
    <td>NUMPAD 7</td>
  </tr>
  <tr>
    <td>NUMPAD8</td>
    <td>104</td>
    <td>NUMPAD 8</td>
  </tr>
  <tr>
    <td>NUMPAD9</td>
    <td>105</td>
    <td>NUMPAD 9</td>
  </tr>
  <tr>
    <td>MULTIPLY</td>
    <td>106</td>
    <td>MULTIPLY</td>
  </tr>
  <tr>
    <td>ADD</td>
    <td>107</td>
    <td>ADD</td>
  </tr>
  <tr>
    <td>SUBTRACT</td>
    <td>109</td>
    <td>SUBTRACT</td>
  </tr>
  <tr>
    <td>DECIMAL</td>
    <td>110</td>
    <td>DECIMAL POINT</td>
  </tr>
  <tr>
    <td>DIVIDE</td>
    <td>111</td>
    <td>DIVIDE</td>
  </tr>
  <tr>
    <td>F1</td>
    <td>112</td>
    <td>F1</td>
  </tr>
  <tr>
    <td>F2</td>
    <td>113</td>
    <td>F2</td>
  </tr>
  <tr>
    <td>F3</td>
    <td>114</td>
    <td>F3</td>
  </tr>
  <tr>
    <td>F4</td>
    <td>115</td>
    <td>F4</td>
  </tr>
  <tr>
    <td>F5</td>
    <td>116</td>
    <td>F5</td>
  </tr>
  <tr>
    <td>F6</td>
    <td>117</td>
    <td>F6</td>
  </tr>
  <tr>
    <td>F7</td>
    <td>118</td>
    <td>F7</td>
  </tr>
  <tr>
    <td>F8</td>
    <td>119</td>
    <td>F8</td>
  </tr>
  <tr>
    <td>F9</td>
    <td>120</td>
    <td>F9</td>
  </tr>
  <tr>
    <td>F10</td>
    <td>121</td>
    <td>F10</td>
  </tr>
  <tr>
    <td>F11</td>
    <td>122</td>
    <td>F11</td>
  </tr>
  <tr>
    <td>F12</td>
    <td>123</td>
    <td>F12</td>
  </tr>
  <tr>
    <td>NUM_LOCK</td>
    <td>144</td>
    <td>NUM LOCK</td>
  </tr>
  <tr>
    <td>SCROLL_LOCK</td>
    <td>145</td>
    <td>SCROLL LOCK</td>
  </tr>
  <tr>
    <td>VOLUME_UP</td>
    <td>186</td>
    <td>SEMI-COLON</td>
  </tr>
  <tr>
    <td>VOLUME_UP</td>
    <td>187</td>
    <td>EQUAL SIGN</td>
  </tr>
  <tr>
    <td>COMMA</td>
    <td>188</td>
    <td>COMMA</td>
  </tr>
  <tr>
    <td>COMMA</td>
    <td>189</td>
    <td>DASH</td>
  </tr>
  <tr>
    <td>PERIOD</td>
    <td>190</td>
    <td>PERIOD</td>
  </tr>
  <tr>
    <td>SLASH</td>
    <td>191</td>
    <td>FORWARD SLASH</td>
  </tr>
  <tr>
    <td>BACK_QUOTE</td>
    <td>192</td>
    <td>GRAVE ACCENT</td>
  </tr>
  <tr>
    <td>OPEN_BRACKET</td>
    <td>219</td>
    <td>OPEN BRACKET</td>
  </tr>
  <tr>
    <td>BACK_SLASH</td>
    <td>220</td>
    <td>BACK SLASH</td>
  </tr>
  <tr>
    <td>CLOSE_BRACKET</td>
    <td>221</td>
    <td>CLOSE BRAKET</td>
  </tr>
  <tr>
    <td>QUOTE</td>
    <td>222</td>
    <td>SINGLE QUOTE</td>
  </tr>
</table>
