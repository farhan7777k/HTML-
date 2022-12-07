# HTML-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Socialbook - Easy to grow up</title>
    <link rel="stylesheet" href="ST.css">
    <script src="https://kit.fontawesome.com/ebdf4268fa.js" crossorigin="anonymous"></script>
</head>
<body>

    <nav>
        <div class="nav-left">
            <img src="C:\Users\Dell\Desktop\images\logo.png" class="logo">
            <ul>
                <li><img src="C:\Users\Dell\Desktop\images\notification.png"></li>
                <li><img src="C:\Users\Dell\Desktop\images\inbox.png"></li>
                <li><img src="C:\Users\Dell\Desktop\images\video.png"></li>
            </ul>
        </div>
        <div class="nav-right">
            

            <div class="search-box">
                <img src="C:\Users\Dell\Desktop\images\search.png">
                <input type="text" placeholder="search">
            </div>
            <div class="nav-user-icon online" onclick="settingsMenuToggle()">
                <img src="C:\Users\Dell\Desktop\images\profile-pic.png">
            </div>
        </div>
<!---------------------------------------------------- settings-menu------------------------------------------ -->
        <div class="settings-menu">

            <div id="dark-btn" class="dark-btn-on">
                <span></span>
            </div>


            <div class="settings-menu-inner">
                <div class="user-profile">
                    <img src="C:\Users\Dell\Desktop\images\profile-pic.png">
                    <div>
                        <p>John Nicholson</p>
                        <a href="#">See your profile.</a>
                    </div>
                </div>
                <hr>
                <div class="user-profile">
                    <img src="C:\Users\Dell\Desktop\images\feedback.png">
                    <div>
                        <p>Give Feedback</p>
                        <a href="#">Help us to improve the new design</a>
                    </div>
                </div>
                <hr>
            
        
            
            <div class="settings-links">
                <img src="C:\Users\Dell\Desktop\images\setting.png" class="settings-icon">
                <a href="#">Settings & Privacy <img src="C:\Users\Dell\Desktop\images\arrow.png" width="10px"></a>
            </div>
            <div class="settings-links">
                <img src="C:\Users\Dell\Desktop\images\help.png" class="settings-icon">
                <a href="#">Help & Support<img src="C:\Users\Dell\Desktop\images\arrow.png" width="10px"></a>
            </div>
            <div class="settings-links">
                <img src="C:\Users\Dell\Desktop\images\display.png" class="settings-icon">
                <a href="#">Display & Accessibility <img src="C:\Users\Dell\Desktop\images\arrow.png" width="10px"></a>
            </div>
            <div class="settings-links">
                <img src="C:\Users\Dell\Desktop\images\logout.png" class="settings-icon">
                <a href="#">Logout <img src="C:\Users\Dell\Desktop\images\arrow.png" width="10px"></a>
            </div>
        </div>
    </nav>

    <div class="container">
        <div class="left-sidebar">
            <div class="imp-links">
                <a href="#"><img src="C:\Users\Dell\Desktop\images\news.png"> Latest News</a>
                <a href="#"><img src="C:\Users\Dell\Desktop\images\friends.png"> Friends</a>
                <a href="#"><img src="C:\Users\Dell\Desktop\images\group.png"> Group</a>
                <a href="#"><img src="C:\Users\Dell\Desktop\images\marketplace.png"> marketplace</a>
                <a href="#"><img src="C:\Users\Dell\Desktop\images\watch.png"> watch</a>
                <a href="#">See More</a>
            </div>
            <div class="shortcut-links">
                <p>Your shortcut</p>
                <a href="#"><img src="C:\Users\Dell\Desktop\images\shortcut-1.png"> Web Developers</a>
                <a href="#"><img src="C:\Users\Dell\Desktop\images\shortcut-2.png"> Web Design course</a>
                <a href="#"><img src="C:\Users\Dell\Desktop\images\shortcut-3.png"> Full Stack Development</a>
                <a href="#"><img src="C:\Users\Dell\Desktop\images\shortcut-4.png"> Website Experts</a>
            </div>
        </div>
            <div class="main-content">

                 <div class="story-gallery">
                    <div class="story story1">
                        <img src="C:\Users\Dell\Desktop\images\upload.png">
                        <p>Post Story</p>
                    </div>
                    <div class="story story2">
                        <img src="C:\Users\Dell\Desktop\images\member-1.png">
                        <p>Alison</p>
                    </div>
                    <div class="story story3">
                        <img src="C:\Users\Dell\Desktop\images\member-2.png">
                        <p>Jackson</p>
                    </div>
                    <div class="story story4">
                        <img src="C:\Users\Dell\Desktop\images\member-3.png">
                        <p>Samona</p>
                    </div>
                    <div class="story story5">
                        <img src="C:\Users\Dell\Desktop\images\member-4.png">
                        <p>John Doe</p>
                    </div>
                 </div>

                 <div class="write-post-container">
                    <div class="user-profile">
                        <img src="C:\Users\Dell\Desktop\images\profile-pic.png">
                        <div>
                            <p>John Nicholson</p>
                            <small>Public <i class="fa-sharp fa-solid fa-caret-down"></i></small>
                        </div>
                    </div>


                    <div class="post-input-container">
                        <textarea rows="3" placeholder="What's on your mind, John?"></textarea>   
                        <div class="add-post-links">
                            <a href="#"><img src="C:\Users\Dell\Desktop\images\live-video.png">Live video</a>
                            <a href="#"><img src="C:\Users\Dell\Desktop\images\photo.png">Photo/video</a>
                            <a href="#"><img src="C:\Users\Dell\Desktop\images\feeling.png">Feeling/Activity</a>
                        </div>
                    </div>

                 </div>

                 <div class="post-container">
                    <div class="post-row">
                        <div class="user-profile">
                            <img src="C:\Users\Dell\Desktop\images\profile-pic.png">
                            <div>
                                <p>John Nicholson</p>
                                <span>June 24 2022, 13:40 pm</span>
                            </div>
                        </div>
                        <a href="#"><i class="fa-sharp fa-solid fa-ellipsis-v"></i></a>
                    </div>
                    
                    <p class="post-text">Friends <span>@friendship</span> It’s not what we have in life, but who we have in our life that matters. <a 
                    href="#">#Bond</a> <a href="#">#Trend</a></p>
                    <img src="C:\Users\Dell\Desktop\images\feed-image-1.png" class="post-img">

                    <div class="post-row">
                        <div class="activity-icons">
                            <div><img src="C:\Users\Dell\Desktop\images\like-blue.png"> 783</div>
                            <div><img src="C:\Users\Dell\Desktop\images\comments.png"> 45</div>
                            <div><img src="C:\Users\Dell\Desktop\images\share.png"> 74</div>
                        </div>
                        <div class="post-profile-icon">
                            <img src="C:\Users\Dell\Desktop\images\profile-pic.png"><i class="fa-sharp fa-solid fa-caret-down"></i>
                        </div>
                    </div>
                 </div>




                 <div class="post-container">
                    <div class="post-row">
                        <div class="user-profile">
                            <img src="C:\Users\Dell\Desktop\images\profile-pic.png">
                            <div>
                                <p>John Nicholson</p>
                                <span>June 25 2022, 12:33 pm</span>
                            </div>
                        </div>
                        <a href="#"><i class="fa-sharp fa-solid fa-ellipsis-v"></i></a>
                    </div>
                    
                    <p class="post-text"> friends <span>@friendship</span> The best moments with friends are the ones that leave you thinking about them for days afterwards and wishing you could relive them all over again.<a 
                    href="#">#moment</a> </p>
                    <img src="C:\Users\Dell\Desktop\images\feed-image-2.png" class="post-img">

                    <div class="post-row">
                        <div class="activity-icons">
                            <div><img src="C:\Users\Dell\Desktop\images\like.png"> 3,098</div>
                            <div><img src="C:\Users\Dell\Desktop\images\comments.png"> 395</div>
                            <div><img src="C:\Users\Dell\Desktop\images\share.png"> 132</div>
                        </div>
                        <div class="post-profile-icon">
                            <img src="C:\Users\Dell\Desktop\images\profile-pic.png"><i class="fa-sharp fa-solid fa-caret-down"></i>
                        </div>
                    </div>
                 </div>
