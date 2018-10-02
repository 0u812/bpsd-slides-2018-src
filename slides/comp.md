<div class="container">
<div class="containercol">
<img src="resources/comp-full.png"/>
</div>
<div class="verticalcenter">
<img id="img1" style="position:absolute;top:0px;left:500px;;width:50%;height:auto;transform:translate(-590px,-85px) scale(0.5,0.5);" class="fragment viewmaster" src="resources/comp-bistable.png"/>
<img style="position:absolute;top:0px;left:500px;;width:50%;height:auto;transform:translate(-590px,85px) scale(0.5,0.5);" class="fragment viewmaster" src="resources/comp-ffn.png"/>
<img style="position:absolute;top:0px;left:500px;;width:50%;height:auto;transform:translate(-590px,150px) scale(0.5,0.5);" class="fragment viewmaster" src="resources/comp-ring.png"/>
<img style="position:absolute;top:0px;left:500px;;width:50%;height:auto;transform:translate(-590px,320px) scale(0.5,0.5);" class="fragment viewmaster" src="resources/comp-combined.png"/>
<img style="position:absolute;top:0px;left:500px;;width:50%;height:auto;transform:translate(-590px,500px) scale(0.5,0.5);" class="fragment viewmaster" src="resources/comp-phrased.png"/>
</div>
</div>

note:
    Put your speaker notes here.
    You can see them pressing 's'.

    <script>
          last_frag = null;
          Reveal.addEventListener( 'fragmentshown', function( event ) {
            if (event.fragment.classList.contains('viewmaster')) {
              event.fragment.previous = last_frag;
              last_frag = event.fragment;
              if (event.fragment.previous) {
                event.fragment.previous.style.opacity = 0;
              }
              event.fragment.style.transform = 'none';
            }
          } );
          Reveal.addEventListener( 'fragmenthidden', function( event ) {
            // event.fragment = the fragment DOM element
          } );
        </script>