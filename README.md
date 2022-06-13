# html_tag_extraction_in_jsx


```
const createMarkup = (element) => {
    return { __html: element };
  };

 <p> <span
  dangerouslySetInnerHTML={createMarkup(bodyContent?.slice(0, 150))}> 
 </span>...</p>
```
