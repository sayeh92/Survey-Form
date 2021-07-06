# Survey-Form
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="form.css">
    <title>Survey</title>
</head>
<body>
    <h1 id="title">
        NASA Seeks Applicants to Explore Moon, Mars
        </h1>

    <p id="description">
        The survey form is only for educational purposes and has no value behind that.
    </p>

    <div class="container">
        <form id="survey-form">
            <h2>Please Fill the form</h2>
            <fieldset>
                <legend>Personal Information</legend>
                <label for="firstname" id="name-label" class="label">First Name
                <input type="text" name="name" id="firstname" placeholder="Joey" required></label>
                <label for="lastname" id="lastname-label" class="label">Last Name
                <input type="text" name="name" id="lastname" placeholder="Tribbiani" required></label><br>
                <label for="email" id="email-label" class="label">Email
                <input type="email" name="email" id="email" placeholder="joey.tribbiani@yahoo.com" required></label> <br>
                <label for="age" id="age-label" class="label">Age
                <input type="number" name="age" min="20" max="40" id="age" required></label>
                <br>
                <label for="male" id="male-label"
                class="label">Male</label>
                <input type="radio" name="gender" id="male" required>
                <label for="female" id="female-label" class="label">Female
                <input type="radio" name="gender" id="female" required></label>
                <label for="other" id="other-label" class="label">Other
                <input type="radio" name="gender" id="other" required></label>
                <br>
            </fieldset>
        <br>
        <label for="dropdown" id="dropdown-label" class="label">Please select your education</label>
        <br>
        <select id="dropdown" name="dropdown" >
            <option value="High school Diploma">High school Diploma"</option>
            <option value="Bachelor's Degree">Bachelor's Degree</option>
            <option value="Master's Degree">Master's Degree</option>
            <option value="Phd">Phd</option>
        </select>
        <br>
        <h3>Please choose your Hobby</h3>
        <div class="label-checkbox">
        <label for="watching-movie" >
        <input type="checkbox" name="checkbox" value="watching-movie" id="watching-movie" >Watching movie</label><br>
        <label for="eating-pasta">
        <input type="checkbox" name="checkbox" value="eating-pasta" id="eating-pasta"> Eating Pasta</label><br>
        <label for="drinking-coffee">
        <input type="checkbox" name="checkbox" value="drinking-coffee" id="drinking-coffee">Drinking coffee</label><br>
        </div>
        <br>
        <label for="textarea" id="textarea-label">Why do you want to apply for NASA program?</label>
        <br>
        <textarea name="textarea" id="textarea" cols="20" rows="10" placeholder="Why are you perfect for this!" required></textarea><br>
        <button type="submit" id="submit" class="button">submit</button>
        </form>
    </div>
</body>
</html>
