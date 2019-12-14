# ModernSPONews

Written By: Adam Buenz

Site: http://www.office365security.com

The SharePoint modern news experience doesn't contain two ordinary functions found in general news distribution:

1.	Easy to use paging controls based on publication date (to accommodate approval workflows for content)
2.	Printing. But not like printing using a bunch of conversion plugins just a simple to use printing feature.

This spfx extension provides a single toolbar in a convent location styled with bootstrap that allow a user to do both of these actions in one package providing a more useful news media experience increasing adoption by more effectively driving and distributing content. 

The spfx extensions targets only news article via the promoted state field in a parametrized REST call. The before and after news articles are found for an article by indexing this collection with the FileRef property providing the correct URL values. The print function simply finds the canvas areas of interest (via spPageCanvasContent and pageTitle), and empties the contents of the page and inserts a more simple version while calling the print dialog against the current markup. When the page is unloaded it is simply re-fetched which points it back to the original markup. 

Contact adam@sharepointsecurity.com if you are interested in a customized spfx extension or certified Office 365 audit without a bunch of hassle. 
