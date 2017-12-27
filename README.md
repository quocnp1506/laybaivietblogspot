# laybaivietblogspot
JS lấy bài viết Blogspot
<script style="text/javascript">
function showpostcount(json) {
document.write('<center>Tổng số bài: <b>' + parseInt(json.feed.openSearch$totalResults.$t,10)
+ '</b></center>');}</script>
<script src="

http://khodienanh.blogspot.com/feeds/posts/default?alt=json-in-script&callback=showpostcount"></script>



http://khodienanh.blogspot.com/atom.xml?redirect=false&start-index=1&max-results=Y
