# whitepapers
Whitepapers on Docker, the Ecosystem, market analysis &amp; best practices

Multiple file formats here (.pdf,.docx, .md) represent work in progress toward publication in Markdown. 

pandoc can't directly convert .pdf to .md, so conversion took 2 steps:

* in Adobe Acrobat Pro, open the .pdf, then File > Save To Other > Microsoft Word > Word Document
* in Terminal, pandoc state_of_union_containers_pt1.docx -f docx -t markdown -o state_of_union_containers_pt1.md 
(repeat for _pt2)
