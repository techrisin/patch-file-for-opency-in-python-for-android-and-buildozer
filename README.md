When you build android app with python for android p4a or buildozer with latest opencv, you may get the error 

patching file cmake/OpenCVDetectPython.cmake 
Hunk #1 FAILED at 175. 
Hunk #2 FAILED at 244. 
2 out of 2 hunks FAILED 
-- saving rejects to file cmake/OpenCVDetectPython.cmake.rej 
patching file modules/python/CMakeLists.txt

This can be resolvd by copying the patch file to the opencv recipe folder 

Full explanation and reason behind this error is explained in [https://techris.in/python/how-to-solve-hunks-failed-saving-rejects-to-file.html](https://techris.in/python/how-to-solve-hunks-failed-saving-rejects-to-file.html)
