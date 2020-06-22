# h264analyzer


ldecod.exe [-s] -i \<input\>.h264 -o \<output\>.yuv \[-r \<orig\>.yuv\] [-xmltrace \<tracefile\>.xml]

-s silent decode    ommit unnecessary information during decoding (optional)

-i <input>.264  encoded bitstream to decode

-o <output>.yuv output filename for the decoded bitstream
  
-r <orig>.yuv   original decoded file (for PSNR computation) (optional)
  
-xmltrace <tracefile>.xml   filename for the XML tracefile (optional)
  
