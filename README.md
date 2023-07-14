# CSS_Radio Input Button Style
Add CSS input field radius customize 

```HTML

<label class="container">
   <div id="th" class="tool-tip active-tip"> Text here </div>	 
   <input type="radio" class="data-val r-layput active" id="data-1" name="data-1" value="200" style="cursor: pointer;">
   <div class="data-label">Label here</div>
</label>

```

```CSS

/* active layput */
input[type='radio'].active {
  -webkit-appearance: none;
  width: 40px;
  height: 40px;
  border-radius: 50%;
  outline: none;
  box-shadow: inset 0 0 0 0px #0268ff;
}

input[type='radio']:checked.active {
  
}

/* White dot */
input[type='radio']:before {
  content: '';
  display: block;
  width: 30%;
  height: 30%;
  border-radius: 100%;
  margin: 0 auto;
  margin-top: 13px;  
  background-color: white;
}

/* Radio body */
input[type='radio']:checked.active {
  background-color: #0268ff;
}

.r-layput {
   position: relative;
   top: -10px; 
}



```
