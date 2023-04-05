<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8" />
        <meta name="Description" content="Sample Website for learning HTML5 and CSS3" />
        <link rel="stylesheet" href="auto.css" />
        <title>uCorp</title>
    </head>
    <body>
        <header>
            <img src="uCorp-logo-3.png" alt="uCorp logo" />
        </header>
        <nav>
            <p><a class="navlinks" href="http://www.ucorp.biz/course_about.php">About Course</a></p>
            <p><a class="navlinks" href="http://www.ucorp.biz/technology.php">Technology</a></p>
        </nav>
        <section>
            <article>
                <h1>Registration Form</h1>
                <form autocomplete="on">
                    <fieldset name="personal_info">
                        <legend>Personal Information:</legend>
                        <p>
                            <label for="tit">Title: </label>
                            <input list="titles" name="title" id="tit" />
                            <datalist id="titles">
                                <option value="Mr."> </option>
                                <option value="Mrs."> </option>
                                <option value="Ms."> </option>
                            </datalist>
                        </p>
                        <p>
                            <label for="first">First name: </label>
                            <input type="text" name="firstname" id="first" />
                        </p>
                        <p>
                            <label for="last">Last name: </label>
                            <input type="text" name="lastname" id="last" />
                        </p>
                        <p>
                            <label for="db">Date of Birth: </label>
                            <input type="date" name="dob" id="db" />
                        </p>
                        <p>
                            <label for="skill">Best Technical Skill: </label>
                        </p>
                        <p>
                            <textarea name="bestskill" placeholder="Database" maxlength="9" id="skill"></textarea>
                        </p>
                    </fieldset>
                    <fieldset name="other-information">
                        <legend>Other Information:</legend>
                        <p>
                            <label for="tech">How many technologies do you know?: 0 </label>
                            <input type="range" name="technologies" min="0" max="50" value="25" id="tech" /> 10+
                        </p>
                        <p>
                            <label for="num">Age of user: </label>
                            <input type="number" name="age" min="1" max="100" id="num" />
                        </p>
                        <input type="submit" formaction="http://ss1.ciwcertified.com/cgi-bin/process.pl" />
                    </fieldset>
                </form>
            </article>
        </section>
        <footer>
            <p>
                FOLLOW US ON:
            </p>
            <p>
                <a href="https://twitter.com/uCorp4">Twitter</a> | 
                <a href="https://www.linkedin.com/company/ucorporation/">LinkedIn</a> |
                <a href="https://www.instagram.com/ucorp123/">Instagram</a>
            </p>
            <p>
                Copyright &copy; All rights reserved by uCorp
            </p>
        </footer>
    </body>
</html>
