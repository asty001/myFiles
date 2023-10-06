document.body.appendChild(style);

var btn = document.createElement("button");
btn.addEventListener('click', function playAudio(){
                      var audio = new Audio('https://asty001.github.io/myFiles/LightFuryAudios/cute001.mp3');
                      audio.play();
                    });

var image = document.createElement("img");
image.src = "https://asty001.github.io/myFiles/images/lightFury.webp";
btn.appendChild(image);

var box = document.createElement("div");
box.appendChild(btn);
box.id = "boxINcrivel";
document.body.appendChild(box);
