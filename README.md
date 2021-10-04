# Accessing the CSI Web Server

This document outlines a process of accessing and creating a website on the CSI Web Server

## Getting Started

-   Open a new terminal window and execute `ssh USERNAME@www.csdept.csi.cuny.edu`

-   If prompted, type `yes` to trust the RSA fingerprint

-   When prompted, enter your password

-   Once logged in, execute

    ```sh
    mkdir public_html && cd public_html
    ```

-   In the same terminal, copy the template `index.html` file using this command

    ```sh
    wget https://raw.githubusercontent.com/ericbenedetto16/csc490-website/master/index.html
    ```

-   Use `vim index.html` to make any necessary changes to the file

## Resources

-   [Getting Started with Vim](https://www.keycdn.com/blog/vim-commands)

-   [HTML Cheatsheet](https://web.stanford.edu/group/csp/cs21/htmlcheatsheet.pdf)

-   [CSS Cheatsheet](https://websitesetup.org/wp-content/uploads/2019/11/wsu-css-cheat-sheet-gdocs.pdf)

-   [Bootstrap](https://getbootstrap.com/)
