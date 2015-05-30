# Refs

- http://stackoverflow.com/questions/21651956/sony-tv-remote-control-over-upnp
- http://amit.chakradeo.net/2008/12/17/sony-bravia-internet-link-unofficial-api/
- https://wolstenhol.me/blog/using-tasker-autovoice-yatse-and-xbmc
- http://www.openremote.org/display/forums/Sony+TV+HTTP+control
- https://github.com/shabunin/cf-sonytv/tree/master/scripts
- http://192.168.0.2:52323/dmr.xml
- http://192.168.0.2/cers/ActionList.xml
- http://192.168.0.2/cers/api/register?name=METAL-DEAN&registrationType=initial&deviceId=MediaRemote
- http://stackoverflow.com/questions/21651956/sony-tv-remote-control-over-upnp
- http://192.168.0.2:80/cers/api/getRemoteCommandList
- http://192.168.0.2/cers/api/getSystemInformation
- http://192.168.0.2:52323/MediaRenderer_32x32.jpg
- https://github.com/chr15m/media-remote/blob/master/SNIFF.md

Get Command List:

        GET http://192.168.0.2/cers/api/getRemoteCommandList
        X-CERS-DEVICE-ID MediaRemote
        X-CERS-DEVICE-INFO test

    <?xml version="1.0"?>
    <remoteCommandList>
        <command name="Confirm" type="ircc" value="AAAAAQAAAAEAAABlAw==" />
        <command name="Up" type="ircc" value="AAAAAQAAAAEAAAB0Aw==" />
        <command name="Down" type="ircc" value="AAAAAQAAAAEAAAB1Aw==" />
        <command name="Right" type="ircc" value="AAAAAQAAAAEAAAAzAw==" />
        <command name="Left" type="ircc" value="AAAAAQAAAAEAAAA0Aw==" />
        <command name="Home" type="ircc" value="AAAAAQAAAAEAAABgAw==" />
        <command name="Options" type="ircc" value="AAAAAgAAAJcAAAA2Aw==" />
        <command name="Return" type="ircc" value="AAAAAgAAAJcAAAAjAw==" />
        <command name="Num1" type="ircc" value="AAAAAQAAAAEAAAAAAw==" />
        <command name="Num2" type="ircc" value="AAAAAQAAAAEAAAABAw==" />
        <command name="Num3" type="ircc" value="AAAAAQAAAAEAAAACAw==" />
        <command name="Num4" type="ircc" value="AAAAAQAAAAEAAAADAw==" />
        <command name="Num5" type="ircc" value="AAAAAQAAAAEAAAAEAw==" />
        <command name="Num6" type="ircc" value="AAAAAQAAAAEAAAAFAw==" />
        <command name="Num7" type="ircc" value="AAAAAQAAAAEAAAAGAw==" />
        <command name="Num8" type="ircc" value="AAAAAQAAAAEAAAAHAw==" />
        <command name="Num9" type="ircc" value="AAAAAQAAAAEAAAAIAw==" />
        <command name="Num0" type="ircc" value="AAAAAQAAAAEAAAAJAw==" />
        <command name="Num11" type="ircc" value="AAAAAQAAAAEAAAAKAw==" />
        <command name="Num12" type="ircc" value="AAAAAQAAAAEAAAALAw==" />
        <command name="Power" type="ircc" value="AAAAAQAAAAEAAAAVAw==" />
        <command name="Display" type="ircc" value="AAAAAQAAAAEAAAA6Aw==" />
        <command name="VolumeUp" type="ircc" value="AAAAAQAAAAEAAAASAw==" />
        <command name="VolumeDown" type="ircc" value="AAAAAQAAAAEAAAATAw==" />
        <command name="Mute" type="ircc" value="AAAAAQAAAAEAAAAUAw==" />
        <command name="Audio" type="ircc" value="AAAAAQAAAAEAAAAXAw==" />
        <command name="SubTitle" type="ircc" value="AAAAAgAAAJcAAAAoAw==" />
        <command name="Yellow" type="ircc" value="AAAAAgAAAJcAAAAnAw==" />
        <command name="Blue" type="ircc" value="AAAAAgAAAJcAAAAkAw==" />
        <command name="Red" type="ircc" value="AAAAAgAAAJcAAAAlAw==" />
        <command name="Green" type="ircc" value="AAAAAgAAAJcAAAAmAw==" />
        <command name="Play" type="ircc" value="AAAAAgAAAJcAAAAaAw==" />
        <command name="Stop" type="ircc" value="AAAAAgAAAJcAAAAYAw==" />
        <command name="Pause" type="ircc" value="AAAAAgAAAJcAAAAZAw==" />
        <command name="Rewind" type="ircc" value="AAAAAgAAAJcAAAAbAw==" />
        <command name="Forward" type="ircc" value="AAAAAgAAAJcAAAAcAw==" />
        <command name="Prev" type="ircc" value="AAAAAgAAAJcAAAA8Aw==" />
        <command name="Next" type="ircc" value="AAAAAgAAAJcAAAA9Aw==" />
        <command name="Replay" type="ircc" value="AAAAAgAAAJcAAAB5Aw==" />
        <command name="Advance" type="ircc" value="AAAAAgAAAJcAAAB4Aw==" />
        <command name="TopMenu" type="ircc" value="AAAAAgAAABoAAABgAw==" />
        <command name="PopUpMenu" type="ircc" value="AAAAAgAAABoAAABhAw==" />
        <command name="Eject" type="ircc" value="AAAAAgAAAJcAAABIAw==" />
        <command name="Rec" type="ircc" value="AAAAAgAAAJcAAAAgAw==" />
        <command name="SyncMenu" type="ircc" value="AAAAAgAAABoAAABYAw==" />
        <command name="ClosedCaption" type="ircc" value="AAAAAgAAAKQAAAAQAw==" />
        <command name="Teletext" type="ircc" value="AAAAAQAAAAEAAAA/Aw==" />
        <command name="ChannelUp" type="ircc" value="AAAAAQAAAAEAAAAQAw==" />
        <command name="ChannelDown" type="ircc" value="AAAAAQAAAAEAAAARAw==" />
        <command name="Input" type="ircc" value="AAAAAQAAAAEAAAAlAw==" />
        <command name="GGuide" type="ircc" value="AAAAAQAAAAEAAAAOAw==" />
        <command name="EPG" type="ircc" value="AAAAAgAAAKQAAABbAw==" />
        <command name="DOT" type="ircc" value="AAAAAgAAAJcAAAAdAw==" />
        <command name="Analog" type="ircc" value="AAAAAgAAAHcAAAANAw==" />
        <command name="Exit" type="ircc" value="AAAAAQAAAAEAAABjAw==" />
        <command name="Digital" type="ircc" value="AAAAAgAAAJcAAAAyAw==" />
        <command name="BS" type="ircc" value="AAAAAgAAAJcAAAAsAw==" />
        <command name="CS" type="ircc" value="AAAAAgAAAJcAAAArAw==" />
        <command name="BSCS" type="ircc" value="AAAAAgAAAJcAAAAQAw==" />
        <command name="Ddata" type="ircc" value="AAAAAgAAAJcAAAAVAw==" />
        <command name="InternetWidgets" type="ircc" value="AAAAAgAAABoAAAB6Aw==" />
        <command name="InternetVideo" type="ircc" value="AAAAAgAAABoAAAB5Aw==" />
        <command name="SceneSelect" type="ircc" value="AAAAAgAAABoAAAB4Aw==" />
        <command name="Mode3D" type="ircc" value="AAAAAgAAAHcAAABNAw==" />
        <command name="iManual" type="ircc" value="AAAAAgAAABoAAAB7Aw==" />
        <command name="Wide" type="ircc" value="AAAAAgAAAKQAAAA9Aw==" />
        <command name="Jump" type="ircc" value="AAAAAQAAAAEAAAA7Aw==" />
        <command name="PAP" type="ircc" value="AAAAAgAAAKQAAAB3Aw==" />
        <command name="MyEPG" type="ircc" value="AAAAAgAAAHcAAABrAw==" />
        <command name="ProgramDescription" type="ircc" value="AAAAAgAAAJcAAAAWAw==" />
        <command name="WriteChapter" type="ircc" value="AAAAAgAAAHcAAABsAw==" />
        <command name="TrackID" type="ircc" value="AAAAAgAAABoAAAB+Aw==" />
        <command name="TenKey" type="ircc" value="AAAAAgAAAJcAAAAMAw==" />
        <command name="AppliCast" type="ircc" value="AAAAAgAAABoAAABvAw==" />
        <command name="acTVila" type="ircc" value="AAAAAgAAABoAAAByAw==" />
        <command name="DeleteVideo" type="ircc" value="AAAAAgAAAHcAAAAfAw==" />
        <command name="EasyStartUp" type="ircc" value="AAAAAgAAAHcAAABqAw==" />
        <command name="OneTouchTimeRec" type="ircc" value="AAAAAgAAABoAAABkAw==" />
        <command name="OneTouchView" type="ircc" value="AAAAAgAAABoAAABlAw==" />
        <command name="OneTouchRec" type="ircc" value="AAAAAgAAABoAAABiAw==" />
        <command name="OneTouchRecStop" type="ircc" value="AAAAAgAAABoAAABjAw==" />
        <command name="MuteOn" type="url" value="http://192.168.0.2:80/cers/command/MuteOn" />
        <command name="MuteOff" type="url" value="http://192.168.0.2:80/cers/command/MuteOff" />
    </remoteCommandList>
