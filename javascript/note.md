## HTML video tag - change source on viewport without media attribute
  * if (matchMedia) {
    var mq = window.matchMedia("(min-width: 600px)");
    mq.addListener(WidthChange);
  }

    function WidthChange(mq) {
        if (mq.matches) {
        // set source to desktop
        } else {
        // set source to mobile
    }
    }

### 
