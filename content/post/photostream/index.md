+++
title = 'Photostream'
summary = 'A selection of my most okayest photos.'
# tags = [
#     "SQL Server",
#     "Debugging",
#     "Database Management",
#     "Backups",
#     "Database Restore"
# ]
# keywords = [
#     "SQL Server backups",
#     "debugging with SQL Server",
#     "SQL Server debugging tools",
#     "database management",
#     "Azure SQL Edge backups",
#     "SQL backup commands",
#     "optimize debugging",
#     "SQL Server restore database",
#     "database snapshots vs backups",
#     "SQL Server backup techniques"
# ]
layout = 'photoList'
categories = ['photography']
lastmod = 2024-04-28
draft = true
showPostNavLinks = false
showShareButtons = false
disableShare = true
comments = false
hideMeta = true
showToc = false
#hiddenInHomeList = true
+++

`exiftool *${@:1} .jpg -json -EXIF:All -struct -w %f.%e.json -XMP:Title -Composite:LensSpec -overwrite_original_in_place`
