<!--@include: @/parts/module/command/chatsetting.md#title-->
<!--@include: @/parts/words.md#path--> `localizations > en_us.yml > command.chatsetting`

<!--@include: @/parts/module/command/chatsetting.md#explanation-->

<!--@include: @/parts/words.md#edit-->
```yaml
<en_us.command.chatsetting>
```

<!--@include: @/parts/words.md#default-->
```yaml
chatsetting:
  no-permission: "<color:#ff7171><b>⁉</b> No permission to change this setting"
  disable:
    you: "<color:#ff7171><b>⁉</b> Display of this command is disabled, check /chatsetting"
    he: "<color:#ff7171><b>⁉</b> He disabled this option via /chatsetting"
    server: "<color:#ff7171><b>⁉</b> This command disabled on server"
  header: "            Chat Settings"
  settings:
    CHAT:
      - - "<fcolor:2>Chat"
        - "<fcolor:1>Your chat <bold><chat>"
    COLOR:
      - - "<fcolor:2>Colors"
        - "<fcolor:1>message"
        - "<fcolor:2>message"
        - "<fcolor:3>message"
        - "<fcolor:4>message"
    STREAM:
      - - "<fcolor:2>Stream"
        - "<color:#98FB98>You're streaming"
      - - "<fcolor:2>Stream"
        - "<color:#ff7171>You don't stream"
    SPY:
      - - "<fcolor:2>Spy"
        - "<color:#98FB98>You're spying"
      - - "<fcolor:2>Spy"
        - "<color:#ff7171>You're not spying"
    ADVANCEMENT:
      - - "<fcolor:2>Advancement"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Advancement"
        - "<color:#ff7171>Display disabled"
    DEATH:
      - - "<fcolor:2>Death"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Death"
        - "<color:#ff7171>Display disabled"
    JOIN:
      - - "<fcolor:2>Join"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Join"
        - "<color:#ff7171>Display disabled"
    QUIT:
      - - "<fcolor:2>Quit"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Quit"
        - "<color:#ff7171>Display disabled"
    AUTO:
      - - "<fcolor:2>Auto Message"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Auto Message"
        - "<color:#ff7171>Display disabled"
    ME:
      - - "<fcolor:2>Command /me"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Command /me"
        - "<color:#ff7171>Display disabled"
    TRY:
      - - "<fcolor:2>Command /try"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Command /try"
        - "<color:#ff7171>Display disabled"
    DICE:
      - - "<fcolor:2>Command /dice"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Command /dice"
        - "<color:#ff7171>Display disabled"
    BALL:
      - - "<fcolor:2>Command /ball"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Command /ball"
        - "<color:#ff7171>Display disabled"
    MUTE:
      - - "<fcolor:2>Command /mute"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Command /mute"
        - "<color:#ff7171>Display disabled"
    BAN:
      - - "<fcolor:2>Command /ban"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Command /ban"
        - "<color:#ff7171>Display disabled"
    WARN:
      - - "<fcolor:2>Command /warn"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Command /warn"
        - "<color:#ff7171>Display disabled"
    TELL:
      - - "<fcolor:2>Command /tell"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Command /tell"
        - "<color:#ff7171>Display disabled"
    REPLY:
      - - "<fcolor:2>Command /reply"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Command /reply"
        - "<color:#ff7171>Display disabled"
    MAIL:
      - - "<fcolor:2>Command /mail"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Command /mail"
        - "<color:#ff7171>Display disabled"
    TICTACTOE:
      - - "<fcolor:2>Command /tictactoe"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Command /tictactoe"
        - "<color:#ff7171>Display disabled"
    KICK:
      - - "<fcolor:2>Command /kick"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Command /kick"
        - "<color:#ff7171>Display disabled"
    TRANSLATETO:
      - - "<fcolor:2>Command /translateto"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Command /translateto"
        - "<color:#ff7171>Display disabled"
    BROADCAST:
      - - "<fcolor:2>Command /broadcast"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Command /broadcast"
        - "<color:#ff7171>Display disabled"
    DO:
      - - "<fcolor:2>Command /do"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Command /do"
        - "<color:#ff7171>Display disabled"
    COIN:
      - - "<fcolor:2>Command /coin"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Command /coin"
        - "<color:#ff7171>Display disabled"
    AFK:
      - - "<fcolor:2>Command /afk"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Command /afk"
        - "<color:#ff7171>Display disabled"
    POLL:
      - - "<fcolor:2>Command /poll"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Command /poll"
        - "<color:#ff7171>Display disabled"
    SPIT:
      - - "<fcolor:2>Command /spit"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Command /spit"
        - "<color:#ff7171>Display disabled"
    GREETING:
      - - "<fcolor:2>Greeting message"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Greeting message"
        - "<color:#ff7171>Display disabled"
    ROCKPAPERSCISSORS:
      - - "<fcolor:2>Command /rockpaperscissors"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Command /rockpaperscissors"
        - "<color:#ff7171>Display disabled"
    DISCORD:
      - - "<fcolor:2>Messages for/from Discord"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Messages for/from Discord"
        - "<color:#ff7171>Display disabled"
    TELEGRAM:
      - - "<fcolor:2>Messages for/from Telegram"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Messages for/from Telegram"
        - "<color:#ff7171>Display disabled"
    TWITCH:
      - - "<fcolor:2>Messages for/from Twitch"
        - "<color:#98FB98>Display enabled"
      - - "<fcolor:2>Messages for/from Twitch"
        - "<color:#ff7171>Display disabled"
```

<!--@include: @/parts/module/command/chatsetting.md#parameters-->
<!--@include: @/parts/module/command/chatsetting.md#localization-->

