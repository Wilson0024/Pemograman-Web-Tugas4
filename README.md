# Web Programming Assignments 4

Welcome to my web programming assignments 4 repository!

![Banner](https://c.tenor.com/bCfpwMjfAi0AAAAC/tenor.gif)

## Personal Information
- **Name**: Wilson Angelie Tan
- **NPM**: 140810230024
- **Class**: B
- **University**: Universitas Padjadjaran
- **Department**: Informatics Engineering

---

## Project Description

This project demonstrates the use of a **HTML form** with the **POST method** to send user input data to a PHP script, which processes and displays the submitted data. It consists of an HTML page containing a form and a PHP script to handle the form data.

### Features
- Collects personal information such as:
  1. **NPM** (Student ID)
  2. **Name**
  3. **Address**
  4. **Place of Birth**
  5. **Date of Birth**
  6. **Gender** (Radio selection)
  7. **Hobby**
  
- The submitted data is processed using PHP and the name and address fields are converted to uppercase before being displayed.

### How It Works
1. **HTML Form**:
   - A form is created using `input` fields, and when the user clicks the **Submit** button, the data is sent to the PHP script using the **POST method**. This ensures that the data is passed securely and is not visible in the URL.
   
2. **PHP Script**:
   - The PHP script (`hasil_form.php`) retrieves the form data using `$_POST[]` and processes it. The `nama` (name) and `alamat` (address) fields are converted to uppercase using the `strtoupper()` function before displaying the result.
   - The script also checks if the form was submitted using the `POST` method. If not, an error message is shown.

### Example Output

After submitting the form, the PHP script will display the following output:

```plaintext
Hasil Input:
NPM: 140810230024
Nama: WILSON ANGELIE TAN
Alamat: BANDUNG
Tempat Lahir: Bandung
Tanggal Lahir: 2000-01-01
Jenis Kelamin: Laki-laki
Hobi: Reading
