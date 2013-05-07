form  與  submit/button clickk事件之關係

**探討form中input輸入值之後直接按enter之行為(這裡的這裡的clickk皆是指第一個type為submit之button/input)
1.一個網頁中存在一在一form，其中包括一個text input(必要條件)，與submit button
IE8--trigger .submit()
IE9--trigger .submit()和.click()
FF--trigger .submit()和.click()
2.一個網頁中存在一在一form，其中包括多個text input(必要條件)，與submit button
IE8--trigger .submit()和.click()
IE9--trigger .submit()和.click()
FF--trigger .submit()和.click()
3.一個網頁中存在一在一form，其中包括一個text input(必要條件)，submit button放置form外面(必要條件)
IE8--trigger .submit()
IE9--trigger .submit()
FF--trigger .submit()
4.一個網頁中存在一在一form，其中包括多個text input(必要條件)，submit button放置form外面(必要條件)
IE8--無反應
IE9--無反應
FF--無反應
5.只要submit button放置放置外面---click button皆不會trigger .submit()...
