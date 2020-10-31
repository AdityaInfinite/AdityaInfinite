### Hi

<!--
**AdityaInfinite/AdityaInfinite** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
--!>

- I’m a noob and I like making and breaking stuff.
- https://adityainfinite.github.io/
<html>
 <p id="repos">hii</p>
    <script>
        func1();
        async function func1() {
            const response = await fetch("https://api.github.com/users/AdityaInfinite");
            var data = await response.json();
            console.log("repos: "+data.public_repos);
            document.getElementById("repos").innerHTML=data.public_repos;
        }
    </script>
  </html>
