# programmer
different thinking
--Created By insta:NamatDimonKing
gg.alert("💥💥 Script Load Successfully 💥💥\n\n                          Created By Honey Pots ")
gg.setVisible(false)
PUBGMH = 1
function HOME()
  Menu = gg.choice({
    "🏙️🏙️Wall 🔑 Hack🏚️🏚️",
    "🎨🎨Color🛡️ Hack🧡🧡",
    "🔐🔐Aimlock 🗡️ Hack🔐🔐",
    "☣️☣️Headshot☣️☣️",
    "🔫🔫Magic 👑 Bullet💣💣",
    "Exit"
  },nil,"🔥🔥🔥 Main Menu 🔥🔥🔥 \n\n--- Created insta:NamatDimonKing")
  if Menu == nil then
  else
    if Menu == 1 then
      WH()
    end
    if Menu == 2 then
      CH()
    end
    if Menu == 3 then
      AL()
    end
    if Menu == 4 then
      HD()
    end
    if Menu == 5 then
      MB()
    end
    if Menu == 6 then
      Abort()
    end
  end
    PUBGMH = -1
   end

   function WH()
     Wall = gg.choice({
      "Snapdragon 730G",
      "All Snapdragon",
      "Other",
      "Back"
     },nil,"WALL HACK Menu")

     if Wall == nil then
      else
        if wall == 1 then
          WHSD730G()
        end
        if Wall == 2 then 
          WHSDA()
        end
        if Wall == 3 then
          WHO()
        end
        if Wall == 4 then
          HOME()
        end
      end
        PUBGMH = -1
   end

   function CH()
     color = gg.choice({
      "Snapdragon 730G",
      "All Snapdragon",
      "Other",
      "Back"
     },nil,"COLOR HACK Menu")

     if color == nil then
      else
        if color == 1 then
          CHSD730G()
        end
        if color == 2 then 
          CHSDA()
        end
        if color == 3 then
          CHO()
        end
        if color == 4 then
          HOME()
        end
      end
        PUBGMH = -1
   end

   function Abort()
       gg.alert("Do You Want To Exit From the Script")
       gg.skipRestoreState()
       gg.setVisible(true)
       os.exit()
     end
     HOME()
     while (true) do
       if gg.isVisible(true) then
         PUBGMH = 1
         gg.setVisible(false)
       end
       gg.clearResults()
       if PUBGMH == 1 then
       HOME()
       end
     end
