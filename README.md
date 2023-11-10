To view and hide the password by changing element type.

Function to view and hide the password

      function showHidePass() {
        // HTMLElement
        const element = document.getElementById("password");

        if (element?.type === "password") {
          element.type = "text";
        } else {
          element.type = "password";
        }
      }
