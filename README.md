# survay-form.css
body {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    color: lavender;
    font-size: 1rem;
}

h1{
    font-weight: 400;
    line-height: 1.2;
}

p{
    font-size: 1.125rem;
}

h1,p{
    margin-top: 0;
    margin-bottom: 0.5rem;
}
body::before {
    content: '';
    position: fixed;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
    z-index: -1;
    background: #1b1b32;
    background-image: linear-gradient(115deg,
            rgba(58, 58, 158, 0.8),
            rgba(136, 136, 206, 0.7)), url(droplets.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
}
.container{
    margin: 3.125rem auto 0 auto;
    width: 100%;
}
header {
    margin-bottom: 1.875rem;
    padding: 0 0.625rem;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

#title {
    text-align: center;
    color: whitesmoke;
}

.description {
    text-align: center;
    font-style: italic;
    color: whitesmoke;
    font-size: x-large;
}

form {
    background-color: rgba(27, 27, 50, 0.8);
    padding: 2.5rem 0.625rem;
    border-radius: 0.25rem;
}

label{
    display: flex;
    align-items: center;
    margin-bottom: 0.5rem;
    font-size: 1.125rem;
}
.form-block {
    display: block;
    min-width: 100%;
    height: 2.375rem;
    padding: 0.375rem 0.175rem;
    color: #495057;
    background-color: #fff;
    background-clip: padding-box;
    border: 1px solid #ced4da;
    border-radius: 0.25rem;
}
.form-block:focus{
    border-color: #1b1b32;
    outline: 0;
    box-shadow: 0 0 0 0.2rem rgba(0, 123, 255, 0.25);
}
input, button, select, textarea {
    line-height: inherit;
    font-size: inherit;
    font-family: inherit;
    margin: 0;
}

.group {
    padding: 0.25rem;
    margin: 0 auto 1.25rem auto;
}

@media (min-width: 576px) {
    .container{
        max-width: 540px;
    }
}
@media (max-width: 768px){
    .container{
        max-width: 720px;
    }
}

@media (min-width: 480px){
    form{
        padding: 2.5rem;
    }
}

.input-textarea{
    min-height: 120px;
    min-width: 100%;
    padding: 0.375rem;
    resize: vertical;
}

button{
    border: none;
    margin:auto;
}

.submit-button{
    display: block;
    width: 100%;
    padding: 0.75rem;
    background:#37af65;
    color: inherit;
    border-radius: 5px;
    cursor: pointer;
}

.input-checkbox, .input-radio{
    display: inline-block;
    margin-right: 0.625rem;
    min-height: 1.25rem;
    min-width: 1.25rem;
}

select{
    display: block;
    min-width: inherit;
    height: 2.375rem;
}
