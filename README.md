LEARNED IN THIS LESSON:


--------------------
setTimeout(function(){
	what.to.do
}, ## how long to do (ms) to do it)

example:

setTimeout(function(){
    modal.style.display = 'inline'
}, 1500)
--------------------


--------------------
element.style.property = 'value'

example:

modal.style.display = 'inline'
--------------------


--------------------
element.classList.toggle('class/id-of-item-to-change')

example:

modalChoiceBtns.classList.toggle('modal-btns-reverse')
--------------------


--------------------
preventDefault()

example:

consentForm.addEventListener('submit', function(e){
    e.preventDefault()
--------------------


--------------------
new FormData & .get()

example:

const consentFormData = new FormData(consentForm)
const fullName = consentFormData.get('fullName')
--------------------


--------------------
required (HTML attributes)

example:

<input type="text" name="fullName" placeholder="Enter your full name" required/>
<input type="email" name="email" placeholder="Enter your email" required/>
--------------------


--------------------
disabled (HTML attribute) & element.disable = true/false

example:

<button class="modal-close-btn" id="modal-close-btn" disabled>X</button>

modalClosedBtn.disabled = false
modalClosedBtn.disabled = true
--------------------