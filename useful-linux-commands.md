# To find and replace a string in multiple files at once:

`find {directory-path} -type -f -print0 | xargs -0 -n 1 sed -i -e 's/{from-string}/{to-string}/g'`
