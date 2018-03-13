# Jekyll
Step by step guide on setting-up personal blog using GitHub Page and Jekyll

- **Jekyll** is static web-page generator from plain text file
- Uses **Liquid** ruby template engine

# Installing Jekyll locally
- Requirement 
        - Ruby latest version
        - Ruby gems (Packaging system for ruby)
        - Jekyll officily supported only on Unix, Linux, Os X
        - Jekyll comes as ruby gems
    
        sudo gem install jekyll

# How Jekyll works ?
- Anything with ```yaml front matter``` is processed by Jekyll.
- File Structure
        1. _config.yml
            Configure file for jekyll.
        2. _layout dir
            layout for jekyll site.
        3. _site dir
            Jekyll generated fully html site, which going to d eploy on github
