@startuml
start
if (Hungry) then (<color:red>yes)
  :Grab a snack!;
(no) elseif (Thirsty) then (<color:blue>yes)
  :Drink something!;
(no) elseif (Sleepy?) then (<color:orange>yes)
  :Take a nap;
(no) elseif (Sad?) then (<color:green>yes)
  :Pet a cat;
  :and a dog;
  :eat some snacks;
else (Content with life?)
  :Good for you :);
endif
  :Everything is fine now;
stop

@enduml
