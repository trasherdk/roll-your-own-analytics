## Roll Your Own Analytics

'''
<script id='ryoa'>
    window.rollyourownanalytics = {};
    window.rollyourownanalytics.url = 'http://localhost:3000'; // Change this line
    var trackjs = document.createElement('script');
    trackjs.src = window.rollyourownanalytics.url + '/track.js';
    trackjs.async = true;
    document.getElementById('ryoa').parentNode.insertBefore(
        trackjs, document.getElementById('ryoa').nextSibling);
</script>
'''