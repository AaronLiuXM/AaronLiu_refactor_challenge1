# Code Refactor Starter Code
--navigation--
replace "div" to header
replace "div" to "nav" in html, update .header "nav" in CSS

--background section--
replace "section class="hero"" to "section id="DitigalMarketingMeeting""

--content--
replace "div" to "main", and "section" 
add img alt="Seo notebook" for "search-engine-optimization"
add img alt="reputation latop" for "online-reputation-management"
add img alt="gathering table" for "social-media-marketing"
    
--benefits--
replace "div" to "aside", and "section"
replace "class" to "id"
add img alt="funnel $" for "benefit-lead"
add img alt="lightbulb" for "benefit-brand"
add img alt="three dollar signs" for "benefit-cost"

--footer--
replace <div> to <footer>

--CSS--
combine #search-engine-optimization img,
        #online-reputation-management img,
        #social-media-marketing img

combine #benefit-lead,
        #benefit-brand,
        #benefit-cost

combine #benefit-lead h3,
        #benefit-brand h3,
        #benefit-cost h3

combine #benefit-lead img,
        #benefit-brand img,
        #benefit-cost img

combine #search-engine-optimization,
        #online-reputation-management,
        #social-media-marketing

combine #search-engine-optimization h2,
        #online-reputation-management h2,
        #social-media-marketing h2

rearrange lines following global->head->body->footer

