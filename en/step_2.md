<html>
<div id="video-container">
    <iframe id="youtube-video" width="560" height="315" src="https://www.youtube.com/embed/m6By70PqVbc" frameborder="0" allowfullscreen cc_load_policy=1
    </iframe>
    
<video id="fallback-video" width="960" height="540" controls>
    <source src="images/step1.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
</div>

<script>
    document.getElementById('youtube-video').onerror = function() {
        document.getElementById('youtube-video').style.display = 'none';
        document.getElementById('fallback-video').style.display = 'block';
    };
</script>
<html>


