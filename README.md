# Converting Powerpoint files (pptx) into Markdown format

The plan is to migrate pptx files into sustainable formats like Markdown (the hidden goal is to reuse presentations frameworks like https://github.com/remarkjs). 
I am relying on this nice library: https://github.com/scanny/python-pptx

So far: 
 * a basic HTML convertion has been implemented 
 * a basic Markdown convertion has been implemented
   * Markdown is a bit specific with page separators, in line with remarkjs behavior
   * some tricks to remove ad-hoc page numbering of Powerpoint (absolutely pointless) or apply some Markdown styles based on font information (if any) 
