const arr = [1, 2, 3, 4, 5];

const result = arr.map(num => num * 2);

console.log(result);



[12/1, 1:49 PM] harsh singh: For flex box 
Html 
<div class="parent">
  <div class="box">Centered</div>
</div>
[12/1, 1:49 PM] harsh singh: .parent {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

<!DOCTYPE html>
<html>
<body>

<h2>Simple Form using Table</h2>

<form>
  <table border="1" cellpadding="5">
    <tr>
      <td>Name</td>
      <td><input type="text" name="name"></td>
    </tr>

    <tr>
      <td>Email</td>
      <td><input type="email" name="email"></td>
    </tr>

    <tr>
      <td>Gender</td>
      <td>
        <input type="radio" name="gender" value="Male"> Male
        <input type="radio" name="gender" value="Female"> Female
      </td>
    </tr>

    <tr>
      <td>Country</td>
      <td>
        <select>
          <option>India</option>
          <option>USA</option>
          <option>UK</option>
        </select>
      </td>
    </tr>

    <tr>
      <td>Message</td>
      <td><textarea rows="3" cols="25"></textarea></td>
    </tr>

    <tr>
      <td colspan="2" align="center">
        <input type="submit" value="Submit">
      </td>
    </tr>
  </table>
</form>

</body>
</html>

const nums = [1, 2, 3, 4];

const sum = nums.reduce((acc, curr) => acc + curr, 0);

console.log(sum); // 10

const people = [
  { name: "Aman", age: 17 },
  { name: "Riya", age: 22 },
  { name: "Bharat", age: 19 }
];

const result = people
  .filter(p => p.age > 18)          // remove kids
  .map(p => p.name.toUpperCase())   // transform names
  .reduce((acc, name) => [...acc, name], []); // gather nicely

console.log(result); // ["RIYA", "BHARAT"]



