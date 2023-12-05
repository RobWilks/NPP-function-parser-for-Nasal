# NPP-function-parser-for-Nasal
Allows Notepad++ to be used for parsing Nasal, a language developed for Flightgear

See NPP notes for creating a customised language parser
https://www.npp-user-manual.org/docs/function-list/

Original Nasal parser created by slaiyer:
https://github.com/slaiyer/nasal-npp

add files overrideMap.xml and nasal.xml to functionList folder in NPP programme folder
example path:
C:\Program Files (x86)\Notepad++\functionList
The above path worked on one NPP installation.  Otherwise try %AppData%\Notepad++. 
See
https://community.notepad-plus-plus.org/topic/15740/faq-what-is-appdata?lang=en-GB
. . . not everyone knows what %AppData% means.
The %xxx% notation is how Windows handles environment variables. %AppData% is one of the standard system environment variables (since at least Windows XP), which expands to the path where Windows likes storing per-application user-data.
