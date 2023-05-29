<!DOCTYPE html>
<html>
  <head>
    <title>Video Call Example</title>
   
  </head>
  <body>
    <audio controls></audio>

    <h1>navigator</h1>
    <button id ="start">start</button>
<button id = "stop">stop</button>
<button id="play">play</button>
   <script>

const start = document.getElementById("start")
const stop = document.getElementById("stop")
const play = document.getElementById("play")



let data  = [];let s;let record;
function starte(){
    console.log("start")
  
    navigator.mediaDevices.getUserMedia({audio:true}).then(stream =>{
    s = stream;
    record = new MediaRecorder(stream);
    record.start();
    record.addEventListener("dataavailable",e =>{
        data.push(e.data)
    })
}).catch(error =>{
    console.log(error)
})


}
function stope(){
    record.stop();
    s.getTracks().forEach(t =>{
        t.stop();
    })
    console.log("stop")
}
function playe() {
  if (data.length === 0) {
    console.warn('No recorded audio available.');
    return;
  }
  console.log("play")
console.log(data)
  // Create a new Blob from the recorded audio chunks
  const audioBlob = new Blob(data, { type: data[0].type });

  // Create a new audio element for playback
  const audioElement = new Audio(URL.createObjectURL(audioBlob));
  audioElement.controls = true;
  audioElement.play();
}


console.log(play,"play")
start.addEventListener("click",starte);
stop.addEventListener("click",stope);
play.addEventListener("click",playe)


   </script>

  </body>
</html>

