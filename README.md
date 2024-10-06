# Job-Application-form
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h2>Job Application</h2>
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name">
        <br/>
        <br/>
        <label for="email">Email:</label>
        <input type="text" name="email" id="email">
        <br/>
        <br/>
        <label for="phone">Phone:</label>
        <input type="tel" name="phone" id="phone">
        <br/>
        <br/>
        <label for="resume">Resume:</label>
        <input type="file" name="resume" id="resume">
        <br/>
        <br/>
        <label for="exp">Experience(years)</label>
        <input type="number" name="exp" id="exp" min="0" max="50">
        <br/>
        <br/>
        <fieldset>
            <legend>Skills</legend>
            <label for="checkbox1">HTML</label>
            <input type="checkbox" id="checkbox1" name="checkbox1">
            <br/>
            <label for="checkbox2">CSS</label>
            <input type="checkbox" id="checkbox2" name="checkbox2">
            <br/>
            <label for="checkbox3">Javascript</label>
            <input type="checkbox" id="checkbox3" name="checkbox3">
        </fieldset>
        <br/>
        <br/>
        <label for="Higheredu">Higher Education</label>
        <select name="Higheredu" id="Higheredu">
            <option value="high">High School</option>
            <option value="">Associate's Degree</option>
            <option value="">Bachleor's Degree</option>
            <option value="">PHd</option>
        </select>
        <br/>
        <br/>
        <fieldset>
            <legend>Availability</legend>
            <label for="half">Full-Time</label>
            <input type="radio" name="half" id="half">
            <br/>
            <label for="part">Part-Time</label>
            <input type="radio" name="part" id="part">
        </fieldset>
        <br/>
        <br/>
        <label for="comments">Additional Comments</label>
        <br/>
        <textarea name="cooments" id="comments" cols="30" rows="30"></textarea>
        <br/>
        <label for="reg">Submit Application</label>
        <input type="submit" name="reg" id="reg">
    </form>
    

</body>
</html>
