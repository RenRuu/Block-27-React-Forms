# Block-27-React-Forms

Forms = are a fundemental part of most web applications, enabling users to input data and interact with apps.
    React provides a convenient and efficient way to handle form input and manage the state of form elements with the "useState" hook. 

    Writing "Controlled" forms using react allows you to create dynamic user interfaces that can handle complex input. 

    Reference HTML Forms: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form

        const [username, setUsername] = useState("")
                can form into the following 
        <input value={username} onChange={ (e)=>{setUsername(e.target.value)}}/>


