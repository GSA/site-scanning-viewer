
- [Copy of the Site Scanning results](https://github.com/GSA/site-scanning-viewer/blob/main/site-scanning-latest.csv)
- [Direct download link](https://raw.githubusercontent.com/GSA/site-scanning-viewer/refs/heads/main/site-scanning-latest.csv)


## Viewer Links
- [Complete Site Scanning results](https://flatgithub.com/GSA/site-scanning-viewer/blob/main/site-scanning-latest.csv?filename=site-scanning-latest.csv)
- [Site Scanning results, filtered to just live production sites](https://flatgithub.com/GSA/site-scanning-viewer/blob/main/site-scanning-latest.csv?filename=site-scanning-latest.csv&filters=live%3DTrue%26filter%3DFalse)
- [Site Scanning results, filtered to just live production sites and deduplicated](https://flatgithub.com/GSA/site-scanning-viewer/blob/main/site-scanning-latest.csv?filename=site-scanning-latest.csv&filters=live%3DTrue%26filter%3DFalse%26redirect%3DFalse)


## How To Create Your Own Viewer Links

Begin with the Viewer Link above, add any additional desired filters (e.g. your agency or a specific domain), copy the URL from the address bar then remove the `&sha=....` string.  Test by opening the url in an incognito/private tab.  

For example, to create a viewer link for GSA data, I would begin with the Complete Site Scanning results link `https://flatgithub.com/GSA/site-scanning-viewer/blob/main/site-scanning-latest.csv?filename=site-scanning-latest.csv`, scroll to the agency column, enter 'general services administration' and then copy out the resulting url: `https://flatgithub.com/GSA/site-scanning-viewer/blob/main/site-scanning-latest.csv?filename=site-scanning-latest.csv&filters=agency%3Dgeneral%2520services%2520administration&sha=e7189ab4cbf7fa30412b4ed0d3fdf9e2bb43e8e2&sort=name%2Casc&stickyColumnName=name`.  

I would then remove the `&sha=....` (and the subsequent parameters for neatness), and would end up with `https://flatgithub.com/GSA/site-scanning-viewer/blob/main/site-scanning-latest.csv?filename=site-scanning-latest.csv&filters=agency%3Dgeneral%2520services%2520administration`. 


As you can see, you can set which field is sticky (remains on the left when scrolling) by clicking on the pushpin icon (resulting in the parameter `&stickyColumnName=`.  Also, the data can be sorted by clicking on the up/down arrows (resulting in the parameter `&sort=`).  
