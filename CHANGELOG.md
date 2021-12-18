## v2021.12.16

- Properly detect exploded Log4J versions (that are not inside *.jar and instead are just sitting as *.class directly on disk).

- Fixed problem that was causing some inner-jar entries to be misread. ("Unexpected end of ZLIB stream").

- All problems now printed on STDERR instead of STDOUT.

- Only check read-permission on files we're interested in (makes for a lot fewer "cannot read!" errors).


