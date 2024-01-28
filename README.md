# removement_URL
How to remove URL from reference list

## in Mendeley

You can remove URLs from a bibliography by opening Mendeley Desktop and clicking View >Citation Style >More Styles, and set Include URLs and Date Accessed in Bibliographies to Only for Webpages.

Reference: http://support.mendeley.com/customer/portal/articles/170063-removing-urls-from-bibliographies-using-the-word-plugin

(This removes URLs from bibliographies created using the plugins and not from the .bib files!

## in Bash

cd Google\ Drive/My\ Drive/pracovni_slozka/publications_mendeley_MAC/Bibtex/
cat mybibfile.bib | sed -e '/url /d' > mybibfile2.bib. 
