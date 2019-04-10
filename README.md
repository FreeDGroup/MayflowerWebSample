# [Travelflan](https://www.travelflan.com/) chatbot widget usage sample for mayflower

## Introduction

This repo demonstrated how to use integrate travelfaln chatbot in for Mayflower's website.

## Run demo
```bash
npm install
npm start
```
then open http://localhost:8080/ in your browser.


## Usage
add this script in the end of your website page.
```bash
<script src="https://alpha-widget.travelflan.com/loader/mayflower/dist/widget.mayflower.min.js"></script>
<script>
  window.TF_CHATBOT.init()
</script>
```
if you want to use this widget in production website, please use
```bash
<script src="https://widget.travelflan.com/loader/mayflower/dist/widget.mayflower.min.js"></script>
<script>
  window.TF_CHATBOT.init({
    environment: 'production'
  })
</script>
```
