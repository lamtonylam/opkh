---
title: Lakisääteiset dokumentit
date: "2018-06-28T00:00:00+01:00"
draft: false
share: false
commentable: false
editable: false

# Optional header image (relative to `static/media/` folder).
header:
  caption: ""
  image: ""

url: "/legal"

---
### [Tietosuojalauseke](/privacy)

### [GDPR-tietosuoja](/gdpr)

### [Käyttöehdot](/terms)

### [Avoimen lähdekoodin lisenssit](/licenses)

<script>
    window.addEventListener('load', function(){
        
        var manager = iframemanager();
        
        // Example with youtube embed
        manager.run({
            currLang: 'en',
            services : {
                youtube : {
                    embedUrl: 'https://www.youtube-nocookie.com/embed/{data-id}',
                    thumbnailUrl: 'https://i3.ytimg.com/vi/{data-id}/hqdefault.jpg',
                    iframe : {
                        allow : 'accelerometer; encrypted-media; gyroscope; picture-in-picture; fullscreen;',
                    },
                    cookie : {
                        name : 'cc_youtube'
                    },
                    languages : {
                        en : {
                            notice: 'This content is hosted by a third party. By showing the external content you accept the <a rel="noreferrer" href="https://www.youtube.com/t/terms" title="Terms and conditions" target="_blank">terms and conditions</a> of youtube.com.',
                            loadBtn: 'Load video',
                            loadAllBtn: 'Don\'t ask again'
                        }
                    }
                }
            }
        });
    });
  </script>

  <div data-service="youtube" data-id="on9TXY8kYyk" data-autoscale></div>