# Project-1
Frontend Practice 1
 This Project was made by Moshood to sharpen his front end skills.





 
/* SM: Phones Landscape / Small Tablets (≤ 768px) */
@media screen and (max-width: 768px) {
    .header-container {
        flex-direction: column;
        align-items: center;
        gap: 1rem;
        padding: 1rem 2rem;
    }

    nav ul {
        flex-direction: column;
        align-items: center;
    }

    #hero {
        flex-direction: column;
        padding: 5rem 2rem;
        gap: 1rem;
        text-align: center;
    }

    .search input {
        width: 100%;
        padding: 0.5rem;
    }

    main {
        flex-direction: column;
        padding: 2rem;
        gap: 2rem;
    }

    .descrip_ {
        width: 100%;
        flex-direction: row;
        align-items: flex-start;
    }

    footer {
        flex-wrap: wrap;
        gap: 2rem;
        padding: 2rem;
    }

    .ft_container {
        width: 45%;
    }
}


/* MD: Tablets and small laptops (≤ 1024px) */
@media screen and (max-width: 1024px) {
    .header-container {
        padding: 1.5rem 2rem;
    }

    #hero {
        flex-direction: column;
        padding: 6rem 3rem;
    }

    .search input {
        padding: 0.5rem 5rem 0.5rem 0.5rem;
    }

    main {
        padding: 3rem;
        gap: 2rem;
    }

    .descrip_ {
        width: 100%;
        justify-content: space-between;
    }

    footer {
        gap: 2rem;
        padding: 2rem 4rem;
    }

    .ft_container {
        width: 30%;
    }
}




/* LG: Default Styles for large screens (> 1024px) */
/* No media query needed — already defined in your main styles */

/* Responsive Styling for Small Screens (≤ 768px) */
@media screen and (max-width: 768px) {

    /* Header layout */
    .header-container {
        flex-direction: column;
        align-items: center;
        gap: 1rem;
        padding: 1rem;
        text-align: center;
    }

    .logo span {
        justify-content: center;
    }

    nav ul {
        flex-direction: column;
        align-items: center;
        gap: 0.5rem;
    }

    /* Hero section */
    #hero {
        flex-direction: column;
        padding: 4rem 1.5rem;
        gap: 2rem;
        text-align: center;
    }

    .search {
        flex-direction: column;
        gap: 0.5rem;
        padding: 1rem;
    }

    .search input {
        width: 100%;
        padding: 0.5rem;
    }

    .search span {
        font-size: 1.5rem;
        cursor: pointer;
    }

    /* Main section layout */
    main {
        flex-direction: column;
        align-items: center;
        padding: 2rem 1rem;
        margin: 2rem 0;
    }

    .descrip_ {
        flex-direction: column;
        width: 100%;
        align-items: center;
        text-align: center;
        gap: 1rem;
    }

    .descrip_ img {
        width: 5rem;
        height: 5rem;
    }

    .text {
        align-items: center;
    }

    .info {
        width: 100%;
    }

    /* Footer layout */
    footer {
        flex-direction: column;
        align-items: center;
        padding: 2rem 1rem;
        gap: 2rem;
        text-align: center;
    }

    .ft_container {
        width: 100%;
    }

    .ft_head {
        font-size: 1.2rem;
    }

    .logoimg {
        width: 2.5rem;
        height: 2.5rem;
    }
}





/* Ultra-Small Screens (≤ 500px) */
@media screen and (max-width: 500px) {

    /* Header and Nav */
    .header-container {
        padding: 0.8rem 1rem;
        gap: 1rem;
    }

    .logo span {
        flex-direction: column;
        font-size: 0.9rem;
        gap: 0.5rem;
    }

    .logoimg {
        width: 2.5rem;
        height: 2.5rem;
    }

    nav ul {
        flex-direction: column;
        align-items: center;
        gap: 0.4rem;
    }

    nav ul li a {
        font-size: 0.85rem;
        padding: 0.4rem 0.8rem;
    }

    /* Hero Section */
    #hero {
        padding: 3rem 1rem;
    }

    .ques h1 {
        font-size: 2.2rem;
    }

    .search {
        flex-direction: column;
        align-items: stretch;
        padding: 0.5rem;
        gap: 0.5rem;
    }

    .search input {
        width: 100%;
        font-size: 1rem;
        padding: 0.6rem;
    }

    .search span {
        font-size: 1.2rem;
        align-self: center;
    }

    /* Main Content Section */
    main {
        padding: 1.5rem 1rem;
        gap: 1.5rem;
    }

    .descrip_ {
        width: 100%;
        flex-direction: column;
        text-align: center;
        gap: 1rem;
    }

    .descrip_ img {
        width: 4.5rem;
        height: 4.5rem;
    }

    .text .head {
        font-size: 1rem;
    }

    .info {
        width: 100%;
        font-size: 0.9rem;
    }

    /* Footer */
    footer {
        flex-direction: column;
        align-items: center;
        padding: 2rem 1rem;
        gap: 2rem;
    }

    .ft_container {
        width: 100%;
    }

    .ft_head {
        font-size: 1.1rem;
    }

    .copyright {
        font-size: 0.85rem;
        line-height: 1.4;
        margin-top: 1rem;
    }
}