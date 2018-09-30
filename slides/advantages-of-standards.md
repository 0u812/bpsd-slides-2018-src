| Standard Encoding | vs. | <div class="container"> <div class="verticalcenter" style="flex-grow:0.3"> <img src="resources/matlab.png" style="width:60%;height:auto"/> </div> <div class="containercol"> Ad-hoc (e.g. with Matlab) </div> </div> |
|---|---|---|
<!--| <span class="fragment" data-fragment-index="1">∙ Composable</span> | <span class="fragment" data-fragment-index="1">∙ Not composable</span> |
| <span class="fragment" data-fragment-index="2">∙ Future-proof</span> | <span class="fragment" data-fragment-index="2">∙ Not future-proof</span> |-->

<div class="container">
<div class="verticalcenter"> <img src="resources/insulin-egfr.png" style="width:70%;height:auto"/> <br/> ∙ Composable </div>
<div class="verticalcenter"> <img src="resources/noble.jpg" style="width:70%;height:auto"/> <br/> ∙ Future-proof </div>
</div>

<span style="font-size:0.75em">Noble, Denis (1960). "Cardiac action and pacemaker potentials based on the Hodgkin-Huxley equations". *Nature*. **188** (4749): 495–7.</span>

note:
    There are a number of reasons to use a standard encoding instead of
    coming up with ad-hoc Matlab code to run your model. Some reasons include:
    * You can re-use smaller models by including them in bigger models, that's composability. For example, if you have a model of the
