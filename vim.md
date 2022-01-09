# VIM

* Line number
  :set nu / :set nonu
* Hex Mode
  :%! xxd / :%! xxd -r
* Search and Replace
  :1,$s/123/456/gc
  :s/123/456/gc
  :%s/123/456/gc
  :%s/,/\r/gc  ', replace to next line'
* Replace with copy content
  viwp
* Copy word
  yiw
* Del in () [] {}
  da(
  da[
  da{
