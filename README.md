ChatWork Client for Google Apps Script

=================

Google App Script Project Key: `M6TcEyniCs1xb3sdXFF_FhI-MNonZQ_sT`

## Usage

```js
// to chatwork
function _sendMessage() {
  
  // settings
  var api_token   = 'xxxxxxxxxxxxxxxxx';
  var room_id     = 123456789;
  var message     = 'message'
  var cw = ChatWorkClient.factory({token: api_token});
  
  // post
  cw.sendMessage({room_id: room_id, body: message});
  
}
```
