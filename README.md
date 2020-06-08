## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/oogwaay/notes/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Two Sum
'vector<int> twoSum(vector<int>& nums, int target) {
        unordered_map<int,int> hm;
        vector<int> res;
        
        for(int i =0; i < nums.size(); i++){
            if(hm.find(target - nums[i]) != hm.end()){
                res.push_back(hm[target-nums[i]]);
                res.push_back(i);
                break;
            }
            if(hm.find(nums[i]) == hm.end()){
                hm.insert(make_pair(nums[i], i));
            }
        }
        
        return res;
}'
## Algorithm
          - Create a Hashmap (value vs index) off all the values from vector.
          - iterate over the vector and find target - value in the Hashmap
          - if found, return the two values. 
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/oogwaay/notes/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
