### Modulo some cosmetic tweaks you can use any webwork site (webwork-2.13 or higher) to render these problems IF it has a course named "daemon_course" with a user "daemon" with privileges greater than a student. 


#Examples of formative use of embedded problems. 

<hr/>

rendered by daemon_course

<iframe  width="800" height="400" 
src="https://demo.webwork.rochester.edu/webwork2/html2xml?
	&answersSubmitted=0&
	&sourceFilePath=Library/Union/setIntFTC/sc5_4_13.pg&
	&problemSeed=123567&
	&courseID=daemon_course&
	&userID=daemon&
	&course_password=daemon&
	&showSummary=1&
	&displayMode=MathJax&
	&problemIdentifierPrefix=102&
	&language=en&
	&outputformat=sticky">
</iframe>

rendered by gage_course

<iframe  width="800" height="400" 
src="https://demo.webwork.rochester.edu/webwork2/html2xml?
	&answersSubmitted=0&
	&sourceFilePath=Library/Union/setIntFTC/sc5_4_13.pg&
	&problemSeed=123567&
	&courseID=gage_course&
	&userID=daemon&
	&course_password=daemon&
	&showSummary=1&
	&displayMode=MathJax&
	&problemIdentifierPrefix=102&
	&language=en&
	&outputformat=sticky">
</iframe>


<hr/>
### same problem rendered on two different sites
##### rendered on demo.webwork.rochester.edu
<iframe  width="800" height="300" 
src="https://demo.webwork.rochester.edu/webwork2/html2xml?
	&answersSubmitted=0&
	&sourceFilePath=Library/ma122DB/set12/s5_4_14.pg&
	&problemSeed=123567&
	&courseID=daemon_course&
	&userID=daemon&
	&course_password=daemon&
	&showSummary=1&
	&displayMode=MathJax&
	&problemIdentifierPrefix=102&
	&language=en&
	&outputformat=sticky">
</iframe>

##### rendered on webwork-ptx.aimath.org

* Notice that ptx uses "anonymous" instead of "daemon"

<iframe  width="800" height="300" 
src="https://webwork-ptx.aimath.org/webwork2/html2xml?
	&answersSubmitted=0&
	&sourceFilePath=Library/ma122DB/set12/s5_4_14.pg&
	&problemSeed=123567&
	&courseID=anonymous&
	&userID=anonymous&
	&course_password=anonymous&
	&showSummary=1&
	&displayMode=MathJax&
	&problemIdentifierPrefix=102&
	&language=en&
	&outputformat=sticky">
</iframe>

<hr/>
##### json_format: output -- thanks to Nathan Wallach and designed eventually for edX problems. Alex Jordan is using a variant for PTX. 
##### rendered on demo.webwork.rochester.edu  
<iframe  width="800" height="600" 
src="https://demo.webwork.rochester.edu/webwork2/html2xml?
	&answersSubmitted=0&
	&sourceFilePath=Library/ma122DB/set12/s5_4_14.pg&
	&problemSeed=123567&
	&courseID=daemon_course&
	&userID=daemon&
	&course_password=daemon&
	&showSummary=1&
	&displayMode=MathJax&
	&problemIdentifierPrefix=102&
	&language=en&
	&outputformat=json">
</iframe>

##### using a base64 encoded problem -- no library is needed -- uses? dangers?

<iframe  width="800" height="400" 
src="https://demo.webwork.rochester.edu/webwork2/html2xml?
	&answersSubmitted=0&
	&problemSeed=123567890&
	&displayMode=MathJax&
	&courseID=daemon_course&
	&userID=daemon&	
	&course_password=daemon&
	&outputformat=simple&
	&problemSource=
IyBERVNDUklQVElPTgojIFByb2JsZW0gZnJvbSBDYWxjdWx1cywgc2luZ2xlIHZhcmlhYmxlLCBI%0AdWdoZXMtSGFsbGV0dCBldCBhbC4sIDR0aCBlZC4KIyBXZUJXb3JLIHByb2JsZW0gd3JpdHRlbiBi%0AeSBHYXZpbiBMYVJvc2UsIDxnbGFyb3NlQHVtaWNoLmVkdT4KIyBFTkRERVNDUklQVElPTgoKIyMg%0AVGFnZ2VkIGJ5IGdsciAwMi8wOC8wOQoKIyMgREJzdWJqZWN0KENhbGN1bHVzIC0gc2luZ2xlIHZh%0AcmlhYmxlKQojIyBEQmNoYXB0ZXIoSW50ZWdyYWxzKQojIyBEQnNlY3Rpb24oUmllbWFubiBzdW1z%0AKQojIyBJbnN0aXR1dGlvbihVbml2ZXJzaXR5IG9mIE1pY2hpZ2FuLCBGb3J0IExld2lzIENvbGxl%0AZ2UpCiMjIEF1dGhvcihHYXZpbiBMYVJvc2UsIFBhdWwgUGVhcnNvbikKIyMgTUxUKHRhYmxlcykK%0AIyMgTGV2ZWwoMikKIyMgTU8oMSkKIyMgVGl0bGVUZXh0MSgnQ2FsY3VsdXMnKQojIyBBdXRob3JU%0AZXh0MSgnSHVnaGVzLUhhbGxldHQnKQojIyBFZGl0aW9uVGV4dDEoJzQnKQojIyBTZWN0aW9uMSgn%0ANS4yJykKIyMgUHJvYmxlbTEoJzcnKQojIyBUaXRsZVRleHQyKCdDYWxjdWx1cycpCiMjIEF1dGhv%0AclRleHQyKCdIdWdoZXMtSGFsbGV0dCcpCiMjIEVkaXRpb25UZXh0MignNScpCiMjIFNlY3Rpb24y%0AKCc1LjInKQojIyBQcm9ibGVtMignOCcpCiMjIEtFWVdPUkRTKCdjYWxjdWx1cycsICdpbnRlZ3Jh%0AbCcsICdkZWZpbml0ZSBpbnRlZ3JhbCcsICdhcmVhJykKCiMjIFRleHRib29rIHRhZ3MKIyMgSEhD%0AaGFwdGVyMSgnS2V5IENvbmNlcHQ6IFRoZSBEZWZpbml0ZSBJbnRlZ3JhbCcpCiMjIEhIQ2hhcHRl%0AcjIoJ0tleSBDb25jZXB0OiBUaGUgRGVmaW5pdGUgSW50ZWdyYWwnKQoKRE9DVU1FTlQoKTsKbG9h%0AZE1hY3JvcygKIlBHc3RhbmRhcmQucGwiLAojIlBHYmFzaWNtYWNyb3MucGwiLAojIlBHY2hvaWNl%0AbWFjcm9zLnBsIiwKIyJQR2Fuc3dlcm1hY3Jvcy5wbCIsCiMiUEdhdXhpbGlhcnlGdW5jdGlvbnMu%0AcGwiLAojIlBHYXN1LnBsIiwgICAgICAgICAgICAgICAjIGdldCBwY19ldmFsdWF0b3IKIk1hdGhP%0AYmplY3RzLnBsIiwKKTsKIApDb250ZXh0KCJOdW1lcmljIik7CgpURVhUKGJlZ2lucHJvYmxlbSgp%0AKTsKJHNob3dQYXJ0aWFsQ29ycmVjdEFuc3dlcnMgPSAxOwoKIyBnZW5lcmF0ZSBhIHRhYmxlIG9m%0AIGRhdGEgZm9yIGYoeCkKQGZkYXRhID0gKCk7CiRmZGF0YVs1XSA9IHJhbmRvbSgxLDEwLDEpOwok%0AZHkgPSByYW5kb20oMTYsMjgsMSk7CmZvciAoIG15ICRpPTQ7ICRpPj0wOyAkaS0tICkgewogICAg%0AJGZkYXRhWyRpXSA9ICRmZGF0YVskaSsxXSArICRkeTsKICAgICRkeSA9IGludCgkZHkvMik7Cn0K%0ACiMgd2UgcHV0IHRoZXNlIGFzIHRoZSBkYXRhIGZvciB4IHZhbHVlcyB3aXRoCiRkeCA9IHJhbmRv%0AbSgyLDQsMSk7CkB4ZGF0YSA9ICggMCwgJGR4LCAyKiRkeCwgMyokZHgsIDQqJGR4LCA1KiRkeCAp%0AOwoKIyB0aGVuIHBvc3NpYmxlIGVzdGltYXRlcyBmb3IgdGhlIGludGVncmFsIGFyZQokbGhzID0g%0AJGR4KigkZmRhdGFbMF0gKyAkZmRhdGFbMV0gKyAkZmRhdGFbMl0gKyAkZmRhdGFbM10gKyAkZmRh%0AdGFbNF0pOwokcmhzID0gJGR4KigkZmRhdGFbMV0gKyAkZmRhdGFbMl0gKyAkZmRhdGFbM10gKyAk%0AZmRhdGFbNF0gKyAkZmRhdGFbNV0pOwokYXZnID0gKCRsaHMgKyAkcmhzKS8yOwoKQ29udGV4dCgp%0ALT50ZXhTdHJpbmdzOwpCRUdJTl9URVhUCgpDb25zaWRlciB0aGUgZm9sbG93aW5nIHRhYmxlOgok%0AUEFSCiRCQ0VOVEVSClx7IGJlZ2ludGFibGUoNykgXH0KXHsgcm93KCAiXCh4XCkiLCBAeGRhdGEg%0AKSBcfQpceyByb3coICJcKGYoeClcKSIsIEBmZGF0YSApIFx9Clx7IGVuZHRhYmxlKCkgXH0KJEVD%0ARU5URVIKJFBBUgooYSkgVXNlIHRoaXMgZGF0YSBhbmQgYSBsZWZ0LWVuZHBvaW50IFJpZW1hbm4g%0Ac3VtIHRvIGVzdGltYXRlIHRoZSBpbnRlZ3JhbDoKJEJSClwoIFxpbnRfMF57JHhkYXRhWzVdfSBm%0AKHgpIFwsIGR4IFxhcHByb3ggXCkgXHsgYW5zX3J1bGUoNDUpIFx9CiRQQVIKKGIpIFVzZSB0aGlz%0AIGRhdGEgYW5kIGEgcmlnaHQtZW5kcG9pbnQgUmllbWFubiBzdW0gdG8gZXN0aW1hdGUgdGhlIGlu%0AdGVncmFsOgokQlIKXCggXGludF8wXnskeGRhdGFbNV19IGYoeCkgXCwgZHggXGFwcHJveCBcKSBc%0AeyBhbnNfcnVsZSg0NSkgXH0KJFBBUgooYykgRmluZCB0aGUgYXZlcmFnZSBvZiB0aGUgbGVmdC0g%0AYW5kIHJpZ2h0LWVuZHBvaW50IFJpZW1hbm4gc3VtcyB0byBlc3RpbWF0ZSB0aGUgaW50ZWdyYWw6%0ACiRCUgpcKCBcaW50XzBeeyR4ZGF0YVs1XX0gZih4KSBcLCBkeCBcYXBwcm94IFwpIFx7IGFuc19y%0AdWxlKDQ1KSBcfQoKCkVORF9URVhUCkNvbnRleHQoKS0%2Bbm9ybWFsU3RyaW5nczsKCkFOUyggQ29t%0AcHV0ZSgiJGxocyIpLT5jbXAodG9sVHlwZT0%2BJ2Fic29sdXRlJyx0b2xlcmFuY2U9PjAuMDEpICk7%0ACkFOUyggQ29tcHV0ZSgiJHJocyIpLT5jbXAodG9sVHlwZT0%2BJ2Fic29sdXRlJyx0b2xlcmFuY2U9%0APjAuMDEpICk7CkFOUyggQ29tcHV0ZSgiJGF2ZyIpLT5jbXAodG9sVHlwZT0%2BJ2Fic29sdXRlJyx0%0Ab2xlcmFuY2U9PjAuMDEpICk7CgojQU5TKHBjX2V2YWx1YXRvciggWyBudW1fY21wKCRsaHMpLCAx%0ALCAnJyBdLAojCQkgICBbIG51bV9jbXAoJHJocyksIDEsICcnIF0sCiMJCSAgIFsgbnVtX2NtcCgk%0AYXZnKSwgMSwgJycgXSApICk7CgoKCkNvbnRleHQoKS0%2BdGV4U3RyaW5nczsKU09MVVRJT04oRVYz%0AKDw8J0VORF9TT0xVVElPTicpKTsKJFBBUiBTT0xVVElPTiAkUEFSCgpXZSBjYW4gZXN0aW1hdGUg%0AdGhlIGludGVncmFsIHdpdGggYSBsZWZ0IG9yIHJpZ2h0IFJpZW1hbm4gc3VtLCBvciB3aXRoIHRo%0AZQphdmVyYWdlIG9mIHRoZSB0d28uICBUaGUgbGVmdCBSaWVtYW5uIHN1bSBpcyAKXFsKXGludF8w%0AXnskeGRhdGFbNV19IGYoeCkgZHggXGFwcHJveAogICgkZHgpKCRmZGF0YVswXSArICRmZGF0YVsx%0AXSArICRmZGF0YVsyXSArICRmZGF0YVszXSArICRmZGF0YVs0XSkgPSAKICAkbGhzLgpcXQpUaGUg%0AcmlnaHQgUmllbWFubiBzdW0gaXMgClxbClxpbnRfMF57JHhkYXRhWzVdfSBmKHgpIGR4IFxhcHBy%0Ab3gKICAoJGR4KSgkZmRhdGFbMV0gKyAkZmRhdGFbMl0gKyAkZmRhdGFbM10gKyAkZmRhdGFbNF0g%0AKyAkZmRhdGFbNV0pID0gCiAgJHJocy4KXF0KVGh1cyB0aGUgYXZlcmFnZSBvZiB0aGUgdHdvIGlz%0AIFwoIFxmcmFjMTIgKCRsaHMgKyAkcmhzKSA9ICRhdmcgXCkuCgpFTkRfU09MVVRJT04KQ29udGV4%0AdCgpLT5ub3JtYWxTdHJpbmdzOwoKCkNPTU1FTlQoJ01hdGhPYmplY3QgdmVyc2lvbicpOwpFTkRE%0AT0NVTUVOVCgpOwoK%0A">
</iframe>	

----
##For JMM presentation:
Here is the magic code for embedding these problems.

```
< iframe  width="800" height="400" 
src="https://demo.webwork.rochester.edu/webwork2/html2xml?
	&answersSubmitted=0&
	&sourceFilePath=Library/Union/setSeriesTaylor/ur_sr_9_6.pg&
	&problemSeed=123567&
	&courseID=daemon_course&
	&userID=daemon&
	&course_password=daemon&
	&showSummary=1&
	&displayMode=MathJax&
	&problemIdentifierPrefix=102&
	&language=en&
	&outputformat=sticky">
< /iframe>
```

