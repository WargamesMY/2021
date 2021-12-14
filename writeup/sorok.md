# Sorok
Challenge source: https://github.com/WargamesMY/2021/blob/main/source/sorok.html

This is some clarification and walkthrough for sorok challenge. This challenge was intended to show how we can hide javascript using unicode tricks in browser.
The WASM in the javascript just to generate flag also if you manage to get the javascript code, you can find it was based on inwasmable from squareCTF. 
Thats why its in misc section, but i guess i failed to demonstrate that, my bad ಥ╭╮ಥ

If you view-source of the index file, you can only see this
![image](https://user-images.githubusercontent.com/1461279/145916115-5d34ec0d-2591-4b5a-af07-18ff84101e17.png)

but if you or change from `eval` to `console.log` you can view the full javascript
![image](https://user-images.githubusercontent.com/1461279/145916722-5528e115-d01f-479e-96a3-95cb05079802.png)

From here you can can get the flag from googling or reversing the WASM.

Ref: 
* https://certitude.consulting/blog/en/invisible-backdoor/
* http://aem1k.com/lions/
* https://squarectf.com/2019/inwasmble.html
