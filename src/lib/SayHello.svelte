<script>
    let person = $state.raw({
        firstName: '',
        lastName: ''
    })

    function sayHello() {   
        person = {
            firstName: document.getElementById("firstName").value,
            lastName: document.getElementById("lastName").value 
        }
    }
    // let person = $state({
    //     firstName: '',
    //     lastName: ''
    // })

    // function sayHello() {   
    //     person.firstName = document.getElementById("firstName").value;
    //     person.lastName = document.getElementById("lastName").value; 
    // }

</script>

<div>
    <input type="text" id="firstName" placeholder="First Name"> <br>
    <input type="text" id="lastName" placeholder="Last Name"> <br>
    <button onclick={sayHello}>Say Hello</button>

    <h1>Hello {person.firstName} {person.lastName}</h1>

</div>