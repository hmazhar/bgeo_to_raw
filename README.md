Compiling
===========
- Requires Partio [https://github.com/wdas/partio/]
- Requires zlib (availible in most linux distributions and homebrew)

Use cmake to generate project/make files and then compile


##bhclassic_to_ascii

Convert a Houdini bhclassic point cloud to an ascii file.

Arguments:
- Input Filename 
- Output Filename 
- Delimiter (optional)

<pre><code>//with custom delimiter
bhclassic_to_ascii input.bhclassic output.txt ,
//without custom delimiter, default is space
bhclassic_to_ascii input.bhclassic output.txt
</code></pre>


Currently outputs position of every point in x y z format with an optional delimiter. 
