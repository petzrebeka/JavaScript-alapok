# JavaScript-alapok
Prooktatás házi feladat JavaScript alapok

<!DOCTYPE html>
<html lang="hu">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Webfejlesztés gyakorlása</title>
    <script>
        // Változók és konstansok
        const myName = "Rebeka";
        const friendName = "Kitti";
        console.log("Az én nevem:", myName);
        console.log("A barátom neve:", friendName);
        
        const PI = 3.14159;
        console.log("A PI értéke:", PI);
        
        // a PI konstans és nem változtatható meg
        
        // Különböző adattípusok
        let age = 23;
        let isStudent = true;
        let hobbies = ["gaming", "edzés", "zene"];
        let address = {
            street: "Nádor utca",
            number: 15,
            city: "Győr"
        };
        
        // Objektumok
        const person = {
            name: "Rebeka",
            age: 23,
            city: "Győr"
        };
        console.log("Person objektum:", person);
        
        // Értékek definiálása
        let initializedVar = "Inicializált változó";
        let emptyVar;
        console.log("Inicializált változó:", initializedVar);
        console.log("Üres változó:", emptyVar); 
        
        // Alap műveletek
        let num1 = 10;
        let num2 = 5;
        console.log("Összeadás:", num1 + num2);
        console.log("Kivonás:", num1 - num2);
        console.log("Szorzás:", num1 * num2);
        console.log("Osztás:", num1 / num2);
        console.log("Maradékos osztás:", num1 % num2);
        
        // Műveleti sorrend
        console.log("Műveleti sorrend 1:", 2 + 3 * 4); 
        console.log("Műveleti sorrend 2:", (2 + 3) * 4); 
        
        // Böngésző interakció
        alert("Üdvözöllek a weboldalon!");
        const userName = prompt("Mi a neved?");
        alert(`Szia ${userName}! Örülök, hogy itt vagy!`);
        console.log(`A felhasználó neve: ${userName}`);
        
        // Elágazások
        const userAge = prompt("Hány éves vagy?");
        if (userAge >= 18) {
            console.log("Hozzáférés engedélyezve.");
            alert("Hozzáférés engedélyezve!");
        } else {
            console.log("Hozzáférés megtagadva: korhatár miatt.");
            alert("Sajnáljuk, de a tartalom csak 18 éven felülieknek elérhető.");
        }
        
        // Összeadás művelet + megjelenítés a kozolban
        const a = 15;
        const b = 7;
        const sum = a + b;
        console.log(`Az összeadás eredménye: ${a} + ${b} = ${sum}`);
    </script>
</head>
<body>
    <h1>Webfejlesztés gyakorlása</h1>
    <p>Petz Rebeka</p>
</body>
</html>
