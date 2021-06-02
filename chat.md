---
layout: default
center: true
---

# Chat

<!-- put this div where you want the chat room to render, it will fill its parent div by default -->


<!-- put this div where you want the chat room to render, it will fill its parent div by default -->
<div style="height:500px">
<div
  id="rml-room-1"
  data-rml-room
  data-rml-version="09.mar.2020"
></div>
</div>

<script>
  window.rmlCalls = window.rmlCalls || {};
  function rml() {
    let ri = arguments[1].roomElementID;
    if (!rmlCalls[ri]) rmlCalls[ri] = [];
    rmlCalls[ri].push(arguments);
  }

  rml('config', {
    options: {
      embedPosition: 'inline',
      collapsedMode: 'none',
      collapsedModeOnlineLabel: 'Ask questions',
      collapsedModeOfflineLabel: 'CS50',
      greetingMessageUsername: 'CS50',
      greetingMessage: ':wave: Discuss here with students and staff!',
    },
    widgetID: 'wgt_c2rqk7jtrec9boumbp10',
    pk: 'sBCxYEHOxd-ZWBGFrcd6hBn4uglrv7RL2DfkwQWb26gm',
    // Replace with the ID of the room-containing element.
    roomElementID: 'rml-room-1',
  });

  // Change userID, username, first and last to your user's ones
  // Change roomKey and roomName to your own ones
  const name = prompt('Name?')
  rml('register', {
    options: {
      userID: '123456',
      username: name,
      // first: 'John',
      // last: 'Smith',
      roomKey: 'CS50',
      roomName: 'CS50 Chat',
    },
    // Replace with the ID of the room-containing element.
    roomElementID: 'rml-room-1',
  });
</script>
<script src="https://embed.roomlio.com/embed.js"></script>
