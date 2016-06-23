# forwardbutton
Intelligently pre-fills the browser forward navigation to enable skipping into the future


This project is crawling out of concept phase. I hope to have an alpha version others can collaborate on by the end of summer (2016). 
Basically it is a chrome extension that reads a page and takes a best guess from all the links as to which one the user will navigate to next and sets the next-page as that link. 
examples: 
  If you're on page 3 of search results and there is a link to page 4, this is likely the next page you will navigate to.
  If you have navigated to chapter 5 from chapter 4, chapter 6 might be in your near future.
  
I hope to have these three functions:
1. AI to make the best guess for the next page (as described above).
2. Profiles of popular sites that include better-than-guesses (i.e. Google results pages and similar).
3. A process to learn a user's behavior, so if you stay on a site for 3 pages, it takes those and generates a profile for that site to better-than-guess for your fourth page.

Some things I could use from anyone who wishes to help:
1. Help in conceptualizing this project and/or describing the vision (if anything is unclear, telling me about it would be very helpful)
2. Additional suggestions for sites that deserve profiles.

Long-term vision: I think it would be wonderful if sites would start using a "next" tag to tell the browser where the most-likely next page would be, and browsers would pre-fill the next navigation with this item. Might be hi-jacked to send you to sponsors or something, but then we could get back to third party extensions like this.
Thank you for reading!


I just found the fastforward-chrome extension here on github. That repo will be very valuable. The difference for my project is I will be comparing the current page url to local links, although the link name might actually be a better idea. Also, I am looking for a way to prefill the forward button with that link. Looks like chrome already enables shift-delete to navigate forward, so that part is already done.
