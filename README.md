# Blog

Building a blog with Evidence. 


## Getting Started


```bash

npm install
npm run sources
npm run dev

```


## Template Layout

The `+layout.svelte` file in `pages` allows to change the layout of the template.

It was used to change the `logo` and `footer`. But also could be used to add analytics library.



## Content

- How/Why we launch the clinic https://chrles.cc/voixlactee / https://voixlactee.ca
- My journey with linux/macos/windows and pc building https://chrles.cc/linux-journey/


## Analytics Client

Posthog integration

```bash

npm install posthog-js

```

Then add this snipet in the `+layout.svelte` and add your Posthog public key

```js

  onMount(async()=>{
    if (browser){
      posthog.init(
      '<YOUR_POSTHOG_KEY>',
      { 
        api_host: 'https://us.i.posthog.com',
        person_profiles: 'identified_only', // or 'always' to create profiles for anonymous users as well
      }
    )
    }
  })


```
