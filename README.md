# Jackson-Pollack
This interactive code follows one's mouse as it randomly draws circles of different sizes and colors on the canvas while also leaving streaks of lines. This digital replication of Jackson Pollack's painting style is a fun way to use html for educational graphic purposes.



var draw = function() {
    
    fill(random(0,200), random(0,200), random(0,200));
    
    ellipse(mouseX, mouseY, random(0,100),random(0,100)); 
    
    line(mouseX, mouseY, random(0,100),random(0,100));

    
    };
