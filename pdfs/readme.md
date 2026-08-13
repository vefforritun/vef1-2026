# PDF útgáfur

Statískar PDF útgáfur af efni, deilt á Canvas.

Útbúnar með pandoc, t.d.

```bash
 pandoc -i vikur/vika-01.md -o pdfs/vika-01.pdf --variable papersize=a4 --variable colorlinks=true -V geometry:margin=1.5cm 
```
