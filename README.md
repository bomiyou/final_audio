# Final project
this is my final _audio_interface_ project.
my main idea was create language learning interface,
where people can listen pronounciation when they click on the letter.

my design plan was simple one page. split 2section,
left side <h1>title: how to read korean</h1>
right side put all korean alphabet, and if user click each of it, they can listen the prounonciation.

fisrt, i set up <div class> seperately and add css,

.split{
  height: 100%;
  width: 50%;
  position: fixed;
  z-index: 1;
  top: 0;
  overflow-x: hidden;
  padding-top: 20px;
}

.left{
  left: 10;
  background-color:#FCFCFC;
}

.right{
  right: 0;
  background-color:#FCFCFC;

}

.centered{
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%,-50%);
 
}

like this, 
however, i was having trouble to make responsive layout, so i changed it.

I recorded audio myself and insert in html with js.

