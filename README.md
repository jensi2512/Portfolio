# Portfolio Responsive Complete
## [Watch it on youtube](https://youtu.be/AKNvTxWOdKw)
### Portfolio Responsive Complete

- Responsive Personal Portfolio Website HTML CSS & JavaScript.
- Contains animations when scrolling.
- Smooth scrolling in each section.
- Developed first with the Mobile First methodology, then for desktop.
- Compatible with all mobile devices and with a beautiful and pleasant user interface.

💙 Join the channel to see more videos like this. [Bedimcode](https://www.youtube.com/@Bedimcode)

![preview img](/preview.png)




.projects {
    padding: 4rem 0;
    text-align: center;
}

.projects__filters {
    margin-bottom: 2rem;
}

.filter-btn {
    border: none;
    padding: 0.5rem 1rem;
    margin: 0 0.5rem;
    background-color: #eee;
    border-radius: 50px;
    cursor: pointer;
    transition: background-color 0.3s;
}

.filter-btn.active, .filter-btn:hover {
    background-color: #007bff;
    color: white;
}

.project-card {
    background: #fff;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    transition: transform 0.3s ease;

    display: flex;              /* make the whole card flex */
    flex-direction: column;     /* stack content vertically */
    height: 100%;               /* equal height */
}


.project-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 20px rgba(0,0,0,0.2);
}

.project-image {
  width: 100%;
  height: 200px;
  background: #f9fafb; /* light bg behind illustrations */
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 12px 12px 0 0;
}

.project-image img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain; /* full image visible */
}



.project-content {
    padding: 1.2rem;
    flex: 1;                    /* grow to fill space */
    display: flex;
    flex-direction: column;
}

.project-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 5%;
}

.project-header h3 {
    font-size: 1.2rem;
    margin: 0;
}

.project-year {
    background-color: #e0e7ff;
    color: #1e40af;
    padding: 0.2rem 0.6rem;
    border-radius: 20px;
    font-size: 0.8rem;
}

.project-content p {
    margin: 0.8rem 0;
    font-size: 0.95rem;
    color: #4b5563;
    text-align: left;
}

.project-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    margin-bottom: 1rem;
}

.project-tags span {
    background-color: #f3f4f6;
    padding: 0.3rem 0.7rem;
    border-radius: 20px;
    font-size: 0.8rem;
    color: #374151;
}

.projects__container {
    display: grid;
    grid-template-columns: repeat(2, 1fr); /* Always 2 per row */
    gap: 2rem;  /* space between cards */
    justify-content: center; /* center grid */
}
.project-card:hover {
    transform: translateY(-5px);
}

.project-footer {
    margin-top: auto;           /* push footer to the bottom */
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.github-link {
    text-decoration: none;
    color: #1f2937;
    font-weight: 500;
    display: flex;
    align-items: center;
    gap: 0.3rem;
}

.view-more {
    text-decoration: none;
    font-size: 1.2rem;
    color: #3b82f6;
}
