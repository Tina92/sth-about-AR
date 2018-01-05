对浏览器来说，WebRTC(Web Real-Time Communication)其实就是提供了3个API：
. MediaStream (即getUserMedia)，用于获取媒体数据，例如来自摄像头和麦克风的视频流和音频流；
. RTCPeerConnection，用于peer跟peer之间呼叫和建立连接以便传输音视频数据流；
. RTCDataChannel，用于peer跟peer之间传输音视频之外的一般数据。