```plantuml
@startuml

repeat:raw data;
if (QC) then (yes)
   :filter;
   :analysis;
   stop
endif
repeat while (redo?) is (yes) not (no)
stop

@enduml
```
