# Test if content is converted to RTF correctly when tbl class is list

    $start
    [1] "{\\rtf1\\ansi\n\\deff0\\deflang1033\n{\\fonttbl{\\f0\\froman\\fcharset161\\fprq2 Times New Roman;}\n{\\f1\\froman\\fcharset161\\fprq2 Times New Roman Greek;}\n{\\f2\\fswiss\\fcharset161\\fprq2 Arial Greek;}\n{\\f3\\fswiss\\fcharset161\\fprq2 Arial;}\n{\\f4\\fswiss\\fcharset161\\fprq2 Helvetica;}\n{\\f5\\fswiss\\fcharset161\\fprq2 Calibri;}\n{\\f6\\froman\\fcharset161\\fprq2 Georgia;}\n{\\f7\\ffroman\\fcharset161\\fprq2 Cambria;}\n{\\f8\\fmodern\\fcharset161\\fprq2 Courier New;}\n{\\f9\\ftech\\fcharset161\\fprq2 Symbol;}\n}\n\n"
    
    $body
    [1] "\\paperw12240\\paperh15840\n\n\\margl1800\\margr1440\\margt2520\\margb1800\\headery2520\\footery1449\n\n\n\n\n\\trowd\\trgaph108\\trleft0\\trqc\n\\clbrdrl\\brdrs\\brdrw15\\clbrdrt\\brdrdb\\brdrw15\\clbrdrr\\brdrs\\brdrw15\\clbrdrb\\brdrw15\\clvertalb\\cellx9000\n\\pard\\hyphpar0\\sb15\\sa15\\fi0\\li0\\ri0\\qc\\fs18{\\f0 X1}\\cell\n\\intbl\\row\\pard\n\\trowd\\trgaph108\\trleft0\\trqc\n\\clbrdrl\\brdrs\\brdrw15\\clbrdrt\\brdrs\\brdrw15\\clbrdrr\\brdrs\\brdrw15\\clbrdrb\\brdrs\\brdrw15\\clvertalt\\cellx9000\n\\pard\\hyphpar0\\sb15\\sa15\\fi0\\li0\\ri0\\qc\\fs18{\\f0 1}\\cell\n\\intbl\\row\\pard\n\n\n\n\n\\paperw12240\\paperh15840\n\n\\margl1800\\margr1440\\margt2520\\margb1800\\headery2520\\footery1449\n\n\n\n\n\\trowd\\trgaph108\\trleft0\\trqc\n\\clbrdrl\\brdrs\\brdrw15\\clbrdrt\\brdrs\\brdrw15\\clbrdrr\\brdrs\\brdrw15\\clbrdrb\\brdrw15\\clvertalb\\cellx9000\n\\pard\\hyphpar0\\sb15\\sa15\\fi0\\li0\\ri0\\qc\\fs18{\\f0 X1}\\cell\n\\intbl\\row\\pard\n\\trowd\\trgaph108\\trleft0\\trqc\n\\clbrdrl\\brdrs\\brdrw15\\clbrdrt\\brdrs\\brdrw15\\clbrdrr\\brdrs\\brdrw15\\clbrdrb\\brdrdb\\brdrw15\\clvertalt\\cellx9000\n\\pard\\hyphpar0\\sb15\\sa15\\fi0\\li0\\ri0\\qc\\fs18{\\f0 1}\\cell\n\\intbl\\row\\pard\n\n\n\n"
    
    $end
    [1] "}"
    

# Test if content is converted to RTF correctly when tbl class is data.frame

    $start
    [1] "{\\rtf1\\ansi\n\\deff0\\deflang1033\n{\\fonttbl{\\f0\\froman\\fcharset161\\fprq2 Times New Roman;}\n{\\f1\\froman\\fcharset161\\fprq2 Times New Roman Greek;}\n{\\f2\\fswiss\\fcharset161\\fprq2 Arial Greek;}\n{\\f3\\fswiss\\fcharset161\\fprq2 Arial;}\n{\\f4\\fswiss\\fcharset161\\fprq2 Helvetica;}\n{\\f5\\fswiss\\fcharset161\\fprq2 Calibri;}\n{\\f6\\froman\\fcharset161\\fprq2 Georgia;}\n{\\f7\\ffroman\\fcharset161\\fprq2 Cambria;}\n{\\f8\\fmodern\\fcharset161\\fprq2 Courier New;}\n{\\f9\\ftech\\fcharset161\\fprq2 Symbol;}\n}\n\n"
    
    $body
    [1] "\\paperw12240\\paperh15840\n\n\\margl1800\\margr1440\\margt2520\\margb1800\\headery2520\\footery1449\n\n\n\n\n\\trowd\\trgaph108\\trleft0\\trqc\n\\clbrdrl\\brdrs\\brdrw15\\clbrdrt\\brdrdb\\brdrw15\\clbrdrb\\brdrw15\\clvertalb\\cellx1800\n\\clbrdrl\\brdrs\\brdrw15\\clbrdrt\\brdrdb\\brdrw15\\clbrdrb\\brdrw15\\clvertalb\\cellx3600\n\\clbrdrl\\brdrs\\brdrw15\\clbrdrt\\brdrdb\\brdrw15\\clbrdrb\\brdrw15\\clvertalb\\cellx5400\n\\clbrdrl\\brdrs\\brdrw15\\clbrdrt\\brdrdb\\brdrw15\\clbrdrb\\brdrw15\\clvertalb\\cellx7200\n\\clbrdrl\\brdrs\\brdrw15\\clbrdrt\\brdrdb\\brdrw15\\clbrdrr\\brdrs\\brdrw15\\clbrdrb\\brdrw15\\clvertalb\\cellx9000\n\\pard\\hyphpar0\\sb15\\sa15\\fi0\\li0\\ri0\\qc\\fs18{\\f0 Sepal.Length}\\cell\n\\pard\\hyphpar0\\sb15\\sa15\\fi0\\li0\\ri0\\qc\\fs18{\\f0 Sepal.Width}\\cell\n\\pard\\hyphpar0\\sb15\\sa15\\fi0\\li0\\ri0\\qc\\fs18{\\f0 Petal.Length}\\cell\n\\pard\\hyphpar0\\sb15\\sa15\\fi0\\li0\\ri0\\qc\\fs18{\\f0 Petal.Width}\\cell\n\\pard\\hyphpar0\\sb15\\sa15\\fi0\\li0\\ri0\\qc\\fs18{\\f0 Species}\\cell\n\\intbl\\row\\pard\n\\trowd\\trgaph108\\trleft0\\trqc\n\\clbrdrl\\brdrs\\brdrw15\\clbrdrt\\brdrs\\brdrw15\\clbrdrb\\brdrw15\\clvertalt\\cellx1800\n\\clbrdrl\\brdrs\\brdrw15\\clbrdrt\\brdrs\\brdrw15\\clbrdrb\\brdrw15\\clvertalt\\cellx3600\n\\clbrdrl\\brdrs\\brdrw15\\clbrdrt\\brdrs\\brdrw15\\clbrdrb\\brdrw15\\clvertalt\\cellx5400\n\\clbrdrl\\brdrs\\brdrw15\\clbrdrt\\brdrs\\brdrw15\\clbrdrb\\brdrw15\\clvertalt\\cellx7200\n\\clbrdrl\\brdrs\\brdrw15\\clbrdrt\\brdrs\\brdrw15\\clbrdrr\\brdrs\\brdrw15\\clbrdrb\\brdrw15\\clvertalt\\cellx9000\n\\pard\\hyphpar0\\sb15\\sa15\\fi0\\li0\\ri0\\qc\\fs18{\\f0 5.1}\\cell\n\\pard\\hyphpar0\\sb15\\sa15\\fi0\\li0\\ri0\\qc\\fs18{\\f0 3.5}\\cell\n\\pard\\hyphpar0\\sb15\\sa15\\fi0\\li0\\ri0\\qc\\fs18{\\f0 1.4}\\cell\n\\pard\\hyphpar0\\sb15\\sa15\\fi0\\li0\\ri0\\qc\\fs18{\\f0 0.2}\\cell\n\\pard\\hyphpar0\\sb15\\sa15\\fi0\\li0\\ri0\\qc\\fs18{\\f0 setosa}\\cell\n\\intbl\\row\\pard\n\\trowd\\trgaph108\\trleft0\\trqc\n\\clbrdrl\\brdrs\\brdrw15\\clbrdrt\\brdrw15\\clbrdrb\\brdrdb\\brdrw15\\clvertalt\\cellx1800\n\\clbrdrl\\brdrs\\brdrw15\\clbrdrt\\brdrw15\\clbrdrb\\brdrdb\\brdrw15\\clvertalt\\cellx3600\n\\clbrdrl\\brdrs\\brdrw15\\clbrdrt\\brdrw15\\clbrdrb\\brdrdb\\brdrw15\\clvertalt\\cellx5400\n\\clbrdrl\\brdrs\\brdrw15\\clbrdrt\\brdrw15\\clbrdrb\\brdrdb\\brdrw15\\clvertalt\\cellx7200\n\\clbrdrl\\brdrs\\brdrw15\\clbrdrt\\brdrw15\\clbrdrr\\brdrs\\brdrw15\\clbrdrb\\brdrdb\\brdrw15\\clvertalt\\cellx9000\n\\pard\\hyphpar0\\sb15\\sa15\\fi0\\li0\\ri0\\qc\\fs18{\\f0 4.9}\\cell\n\\pard\\hyphpar0\\sb15\\sa15\\fi0\\li0\\ri0\\qc\\fs18{\\f0 3}\\cell\n\\pard\\hyphpar0\\sb15\\sa15\\fi0\\li0\\ri0\\qc\\fs18{\\f0 1.4}\\cell\n\\pard\\hyphpar0\\sb15\\sa15\\fi0\\li0\\ri0\\qc\\fs18{\\f0 0.2}\\cell\n\\pard\\hyphpar0\\sb15\\sa15\\fi0\\li0\\ri0\\qc\\fs18{\\f0 setosa}\\cell\n\\intbl\\row\\pard\n\n\n"
    
    $end
    [1] "}"
    
