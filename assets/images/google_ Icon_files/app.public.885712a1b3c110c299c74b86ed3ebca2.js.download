(function(__wpcc){__wpcc.d=__wpcc.d||{};__wpcc.d.scope={};__wpcc.d.createTemplateTagFirstArg=function(a){return a.raw=a};__wpcc.d.createTemplateTagFirstArgWithRaw=function(a,b){a.raw=b;return a};__wpcc.d.getGlobal=function(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");};__wpcc.d.global=__wpcc.d.getGlobal(this);var g;
"undefined"===typeof g&&(g=function(){});g.p="";}).call(this || window, (window.__wpcc = window.__wpcc || {}));

(function(__wpcc){var r=function(a){return h?a instanceof HTMLElement:a&&"object"===typeof a&&null!==a&&1===a.nodeType&&"string"===typeof a.nodeName},t=function(a,b){b.forEach(function(c){a.classList.add(c)})},u=function(a,b){b.forEach(function(c){a.classList.remove(c)})},x=function(){throw Error("Missing parameter");},y=function(a){this.isShowing=!1;var b=void 0===a.namespace?null:a.namespace,c=void 0===a.zoomFactor?x():a.zoomFactor;a=void 0===a.containerEl?x():a.containerEl;this.settings={namespace:b,zoomFactor:c,
containerEl:a};this.openClasses=this._buildClasses("open");this._buildElement()},z=function(a){a=void 0===a?{}:a;this._show=this._show.bind(this);this._hide=this._hide.bind(this);this._handleEntry=this._handleEntry.bind(this);this._handleMovement=this._handleMovement.bind(this);var b=void 0===a.el?x():a.el,c=void 0===a.zoomPane?x():a.zoomPane,e=void 0===a.sourceAttribute?x():a.sourceAttribute,f=void 0===a.handleTouch?x():a.handleTouch,q=void 0===a.onShow?null:a.onShow,k=void 0===a.onHide?null:a.onHide,
v=void 0===a.hoverDelay?0:a.hoverDelay,w=void 0===a.touchDelay?0:a.touchDelay,l=void 0===a.hoverBoundingBox?x():a.hoverBoundingBox,m=void 0===a.touchBoundingBox?x():a.touchBoundingBox,n=void 0===a.namespace?null:a.namespace,p=void 0===a.zoomFactor?x():a.zoomFactor,B=void 0===a.boundingBoxContainer?x():a.boundingBoxContainer;this.settings={el:b,zoomPane:c,sourceAttribute:e,handleTouch:f,onShow:q,onHide:k,hoverDelay:v,touchDelay:w,hoverBoundingBox:l,touchBoundingBox:m,namespace:n,zoomFactor:p,boundingBoxContainer:B,
passive:void 0===a.passive?!1:a.passive};if(this.settings.hoverBoundingBox||this.settings.touchBoundingBox)this.boundingBox=new y({namespace:this.settings.namespace,zoomFactor:this.settings.zoomFactor,containerEl:this.settings.boundingBoxContainer});this.enabled=!0;this._bindEvents()},A=function(a){a=void 0===a?{}:a;this.HAS_ANIMATION=!1;if("undefined"!==typeof document){var b=document.createElement("div").style;this.HAS_ANIMATION="animation"in b||"webkitAnimation"in b}this._completeShow=this._completeShow.bind(this);
this._completeHide=this._completeHide.bind(this);this._handleLoad=this._handleLoad.bind(this);this.isShowing=!1;b=void 0===a.container?null:a.container;var c=void 0===a.zoomFactor?x():a.zoomFactor,e=void 0===a.inline?x():a.inline,f=void 0===a.namespace?null:a.namespace,q=void 0===a.showWhitespaceAtEdges?x():a.showWhitespaceAtEdges,k=void 0===a.containInline?x():a.containInline;this.settings={container:b,zoomFactor:c,inline:e,namespace:f,showWhitespaceAtEdges:q,containInline:k,inlineOffsetX:void 0===
a.inlineOffsetX?0:a.inlineOffsetX,inlineOffsetY:void 0===a.inlineOffsetY?0:a.inlineOffsetY,inlineContainer:void 0===a.inlineContainer?document.body:a.inlineContainer};this.openClasses=this._buildClasses("open");this.openingClasses=this._buildClasses("opening");this.closingClasses=this._buildClasses("closing");this.inlineClasses=this._buildClasses("inline");this.loadingClasses=this._buildClasses("loading");this._buildElement()},C=function(a,b){b=void 0===b?{}:b;this.VERSION="1.5.0";this.triggerEl=
a;this.destroy=this.destroy.bind(this);if(!r(this.triggerEl))throw new TypeError("`new Drift` requires a DOM element as its first argument.");a=b.namespace||null;var c=b.showWhitespaceAtEdges||!1,e=b.containInline||!1,f=b.inlineOffsetX||0,q=b.inlineOffsetY||0,k=b.inlineContainer||document.body,v=b.sourceAttribute||"data-zoom",w=b.zoomFactor||3,l=void 0===b.paneContainer?document.body:b.paneContainer,m=b.inlinePane||375,n="handleTouch"in b?!!b.handleTouch:!0,p=b.onShow||null,B=b.onHide||null,D="injectBaseStyles"in
b?!!b.injectBaseStyles:!0,E=b.hoverDelay||0,F=b.touchDelay||0,G=b.hoverBoundingBox||!1,H=b.touchBoundingBox||!1,I=b.boundingBoxContainer||document.body;b=b.passive||!1;if(!0!==m&&!r(l))throw new TypeError("`paneContainer` must be a DOM element when `inlinePane !== true`");if(!r(k))throw new TypeError("`inlineContainer` must be a DOM element");this.settings={namespace:a,showWhitespaceAtEdges:c,containInline:e,inlineOffsetX:f,inlineOffsetY:q,inlineContainer:k,sourceAttribute:v,zoomFactor:w,paneContainer:l,
inlinePane:m,handleTouch:n,onShow:p,onHide:B,injectBaseStyles:D,hoverDelay:E,touchDelay:F,hoverBoundingBox:G,touchBoundingBox:H,boundingBoxContainer:I,passive:b};this.settings.injectBaseStyles&&!document.querySelector(".drift-base-styles")&&(b=document.createElement("style"),b.type="text/css",b.classList.add("drift-base-styles"),b.appendChild(document.createTextNode(".drift-bounding-box,.drift-zoom-pane{position:absolute;pointer-events:none}@keyframes noop{0%{zoom:1}}@-webkit-keyframes noop{0%{zoom:1}}.drift-zoom-pane.drift-open{display:block}.drift-zoom-pane.drift-closing,.drift-zoom-pane.drift-opening{animation:noop 1ms;-webkit-animation:noop 1ms}.drift-zoom-pane{overflow:hidden;width:100%;height:100%;top:0;left:0}.drift-zoom-pane-loader{display:none}.drift-zoom-pane img{position:absolute;display:block;max-width:none;max-height:none}")),
a=document.head,a.insertBefore(b,a.firstChild));this._buildZoomPane();this._buildTrigger()},h="object"===typeof HTMLElement;y.prototype._buildClasses=function(a){var b=["drift-"+a],c=this.settings.namespace;c&&b.push(c+"-"+a);return b};y.prototype._buildElement=function(){this.el=document.createElement("div");t(this.el,this._buildClasses("bounding-box"))};y.prototype.show=function(a,b){this.isShowing=!0;this.settings.containerEl.appendChild(this.el);var c=this.el.style;c.width=Math.round(a/this.settings.zoomFactor)+"px";c.height=Math.round(b/this.settings.zoomFactor)+"px";t(this.el,this.openClasses)};
y.prototype.hide=function(){this.isShowing&&this.settings.containerEl.removeChild(this.el);this.isShowing=!1;u(this.el,this.openClasses)};
y.prototype.setPosition=function(a,b,c){var e=window.pageXOffset,f=window.pageYOffset;a=c.left+a*c.width-this.el.clientWidth/2+e;b=c.top+b*c.height-this.el.clientHeight/2+f;a<c.left+e?a=c.left+e:a+this.el.clientWidth>c.left+c.width+e&&(a=c.left+c.width-this.el.clientWidth+e);b<c.top+f?b=c.top+f:b+this.el.clientHeight>c.top+c.height+f&&(b=c.top+c.height-this.el.clientHeight+f);this.el.style.left=a+"px";this.el.style.top=b+"px"};z.prototype._preventDefault=function(a){a.preventDefault()};z.prototype._preventDefaultAllowTouchScroll=function(a){this.settings.touchDelay&&this._isTouchEvent(a)&&!this.isShowing||a.preventDefault()};z.prototype._isTouchEvent=function(a){return!!a.touches};
z.prototype._bindEvents=function(){this.settings.el.addEventListener("mouseenter",this._handleEntry);this.settings.el.addEventListener("mouseleave",this._hide);this.settings.el.addEventListener("mousemove",this._handleMovement);var a={passive:this.settings.passive};this.settings.handleTouch?(this.settings.el.addEventListener("touchstart",this._handleEntry,a),this.settings.el.addEventListener("touchend",this._hide),this.settings.el.addEventListener("touchmove",this._handleMovement,a)):(this.settings.el.addEventListener("touchstart",
this._preventDefault,a),this.settings.el.addEventListener("touchend",this._preventDefault),this.settings.el.addEventListener("touchmove",this._preventDefault,a))};
z.prototype._unbindEvents=function(){this.settings.el.removeEventListener("mouseenter",this._handleEntry);this.settings.el.removeEventListener("mouseleave",this._hide);this.settings.el.removeEventListener("mousemove",this._handleMovement);this.settings.handleTouch?(this.settings.el.removeEventListener("touchstart",this._handleEntry),this.settings.el.removeEventListener("touchend",this._hide),this.settings.el.removeEventListener("touchmove",this._handleMovement)):(this.settings.el.removeEventListener("touchstart",
this._preventDefault),this.settings.el.removeEventListener("touchend",this._preventDefault),this.settings.el.removeEventListener("touchmove",this._preventDefault))};z.prototype._handleEntry=function(a){this._preventDefaultAllowTouchScroll(a);this._lastMovement=a;"mouseenter"==a.type&&this.settings.hoverDelay?this.entryTimeout=setTimeout(this._show,this.settings.hoverDelay):this.settings.touchDelay?this.entryTimeout=setTimeout(this._show,this.settings.touchDelay):this._show()};
z.prototype._show=function(){if(this.enabled){var a=this.settings.onShow;a&&"function"===typeof a&&a();this.settings.zoomPane.show(this.settings.el.getAttribute(this.settings.sourceAttribute),this.settings.el.clientWidth,this.settings.el.clientHeight);this._lastMovement&&((a=this._lastMovement.touches)&&this.settings.touchBoundingBox||!a&&this.settings.hoverBoundingBox)&&this.boundingBox.show(this.settings.zoomPane.el.clientWidth,this.settings.zoomPane.el.clientHeight);this._handleMovement()}};
z.prototype._hide=function(a){a&&this._preventDefaultAllowTouchScroll(a);this._lastMovement=null;this.entryTimeout&&clearTimeout(this.entryTimeout);this.boundingBox&&this.boundingBox.hide();(a=this.settings.onHide)&&"function"===typeof a&&a();this.settings.zoomPane.hide()};
z.prototype._handleMovement=function(a){if(a)this._preventDefaultAllowTouchScroll(a),this._lastMovement=a;else if(this._lastMovement)a=this._lastMovement;else return;if(a.touches){a=a.touches[0];var b=a.clientX;var c=a.clientY}else b=a.clientX,c=a.clientY;a=this.settings.el.getBoundingClientRect();b=(b-a.left)/this.settings.el.clientWidth;c=(c-a.top)/this.settings.el.clientHeight;this.boundingBox&&this.boundingBox.setPosition(b,c,a);this.settings.zoomPane.setPosition(b,c,a)};
__wpcc.d.global.Object.defineProperties(z.prototype,{isShowing:{configurable:!0,enumerable:!0,get:function(){return this.settings.zoomPane.isShowing}}});A.prototype._buildClasses=function(a){var b=["drift-"+a],c=this.settings.namespace;c&&b.push(c+"-"+a);return b};A.prototype._buildElement=function(){this.el=document.createElement("div");t(this.el,this._buildClasses("zoom-pane"));var a=document.createElement("div");t(a,this._buildClasses("zoom-pane-loader"));this.el.appendChild(a);this.imgEl=document.createElement("img");this.el.appendChild(this.imgEl)};A.prototype._setImageURL=function(a){this.imgEl.setAttribute("src",a)};
A.prototype._setImageSize=function(a,b){this.imgEl.style.width=a*this.settings.zoomFactor+"px";this.imgEl.style.height=b*this.settings.zoomFactor+"px"};
A.prototype.setPosition=function(a,b,c){var e=this.imgEl.offsetWidth,f=this.imgEl.offsetHeight,q=this.el.offsetWidth,k=this.el.offsetHeight,v=q/2-e*a,w=k/2-f*b,l=q-e,m=k-f,n=0<l,p=0<m;f=n?l/2:0;e=p?m/2:0;l=n?l/2:l;m=p?m/2:m;this.el.parentElement===this.settings.inlineContainer&&(p=window.pageXOffset,n=window.pageYOffset,a=c.left+a*c.width-q/2+this.settings.inlineOffsetX+p,b=c.top+b*c.height-k/2+this.settings.inlineOffsetY+n,this.settings.containInline&&(a<c.left+p?a=c.left+p:a+q>c.left+c.width+p&&
(a=c.left+c.width-q+p),b<c.top+n?b=c.top+n:b+k>c.top+c.height+n&&(b=c.top+c.height-k+n)),this.el.style.left=a+"px",this.el.style.top=b+"px");this.settings.showWhitespaceAtEdges||(v>f?v=f:v<l&&(v=l),w>e?w=e:w<m&&(w=m));this.imgEl.style.transform="translate("+v+"px, "+w+"px)";this.imgEl.style.webkitTransform="translate("+v+"px, "+w+"px)"};
A.prototype._removeListenersAndResetClasses=function(){this.el.removeEventListener("animationend",this._completeShow);this.el.removeEventListener("animationend",this._completeHide);this.el.removeEventListener("webkitAnimationEnd",this._completeShow);this.el.removeEventListener("webkitAnimationEnd",this._completeHide);u(this.el,this.openClasses);u(this.el,this.closingClasses)};
A.prototype.show=function(a,b,c){this._removeListenersAndResetClasses();this.isShowing=!0;t(this.el,this.openClasses);this.imgEl.getAttribute("src")!=a&&(t(this.el,this.loadingClasses),this.imgEl.addEventListener("load",this._handleLoad),this._setImageURL(a));this._setImageSize(b,c);this._isInline?this._showInline():this._showInContainer();this.HAS_ANIMATION&&(this.el.addEventListener("animationend",this._completeShow),this.el.addEventListener("webkitAnimationEnd",this._completeShow),t(this.el,this.openingClasses))};
A.prototype._showInline=function(){this.settings.inlineContainer.appendChild(this.el);t(this.el,this.inlineClasses)};A.prototype._showInContainer=function(){this.settings.container.appendChild(this.el)};
A.prototype.hide=function(){this._removeListenersAndResetClasses();this.isShowing=!1;this.HAS_ANIMATION?(this.el.addEventListener("animationend",this._completeHide),this.el.addEventListener("webkitAnimationEnd",this._completeHide),t(this.el,this.closingClasses)):(u(this.el,this.openClasses),u(this.el,this.inlineClasses))};
A.prototype._completeShow=function(){this.el.removeEventListener("animationend",this._completeShow);this.el.removeEventListener("webkitAnimationEnd",this._completeShow);u(this.el,this.openingClasses)};
A.prototype._completeHide=function(){this.el.removeEventListener("animationend",this._completeHide);this.el.removeEventListener("webkitAnimationEnd",this._completeHide);u(this.el,this.openClasses);u(this.el,this.closingClasses);u(this.el,this.inlineClasses);this.el.style.left="";this.el.style.top="";this.el.parentElement===this.settings.container?this.settings.container.removeChild(this.el):this.el.parentElement===this.settings.inlineContainer&&this.settings.inlineContainer.removeChild(this.el)};
A.prototype._handleLoad=function(){this.imgEl.removeEventListener("load",this._handleLoad);u(this.el,this.loadingClasses)};__wpcc.d.global.Object.defineProperties(A.prototype,{_isInline:{configurable:!0,enumerable:!0,get:function(){var a=this.settings.inline;return!0===a||"number"===typeof a&&window.innerWidth<=a}}});C.prototype._buildZoomPane=function(){this.zoomPane=new A({container:this.settings.paneContainer,zoomFactor:this.settings.zoomFactor,showWhitespaceAtEdges:this.settings.showWhitespaceAtEdges,containInline:this.settings.containInline,inline:this.settings.inlinePane,namespace:this.settings.namespace,inlineOffsetX:this.settings.inlineOffsetX,inlineOffsetY:this.settings.inlineOffsetY,inlineContainer:this.settings.inlineContainer})};
C.prototype._buildTrigger=function(){this.trigger=new z({el:this.triggerEl,zoomPane:this.zoomPane,handleTouch:this.settings.handleTouch,onShow:this.settings.onShow,onHide:this.settings.onHide,sourceAttribute:this.settings.sourceAttribute,hoverDelay:this.settings.hoverDelay,touchDelay:this.settings.touchDelay,hoverBoundingBox:this.settings.hoverBoundingBox,touchBoundingBox:this.settings.touchBoundingBox,namespace:this.settings.namespace,zoomFactor:this.settings.zoomFactor,boundingBoxContainer:this.settings.boundingBoxContainer,
passive:this.settings.passive})};C.prototype.setZoomImageURL=function(a){this.zoomPane._setImageURL(a)};C.prototype.disable=function(){this.trigger.enabled=!1};C.prototype.enable=function(){this.trigger.enabled=!0};C.prototype.destroy=function(){this.trigger._hide();this.trigger._unbindEvents()};
__wpcc.d.global.Object.defineProperties(C.prototype,{isShowing:{configurable:!0,enumerable:!0,get:function(){return this.zoomPane.isShowing}},zoomFactor:{configurable:!0,enumerable:!0,get:function(){return this.settings.zoomFactor},set:function(a){this.settings.zoomFactor=a;this.zoomPane.settings.zoomFactor=a;this.trigger.settings.zoomFactor=a;this.boundingBox.settings.zoomFactor=a}}});Object.defineProperty(C.prototype,"isShowing",{get:function(){return this.isShowing}});
Object.defineProperty(C.prototype,"zoomFactor",{get:function(){return this.zoomFactor},set:function(a){this.zoomFactor=a}});C.prototype.setZoomImageURL=C.prototype.setZoomImageURL;C.prototype.disable=C.prototype.disable;C.prototype.enable=C.prototype.enable;C.prototype.destroy=C.prototype.destroy;window.Drift=C;}).call(this || window, (window.__wpcc = window.__wpcc || {}));

//# sourceMappingURL=Drift.min.js.map
/* Simple JavaScript Inheritance
 * By John Resig http://ejohn.org/
 * MIT Licensed.
 */
// Inspired by base2 and Prototype
(function(){
  var initializing = false, fnTest = /xyz/.test(function(){xyz;}) ? /\b_super\b/ : /.*/;
 
  // The base Class implementation (does nothing)
  this.Class = function(){};
 
  // Create a new Class that inherits from this class
  Class.extend = function(prop) {
    var _super = this.prototype;
   
    // Instantiate a base class (but only create the instance,
    // don't run the init constructor)
    initializing = true;
    var prototype = new this();
    initializing = false;
   
    // Copy the properties over onto the new prototype
    for (var name in prop) {
      // Check if we're overwriting an existing function
      prototype[name] = typeof prop[name] == "function" &&
        typeof _super[name] == "function" && fnTest.test(prop[name]) ?
        (function(name, fn){
          return function() {
            var tmp = this._super;
           
            // Add a new ._super() method that is the same method
            // but on the super-class
            this._super = _super[name];
           
            // The method only need to be bound temporarily, so we
            // remove it when we're done executing
            var ret = fn.apply(this, arguments);        
            this._super = tmp;
           
            return ret;
          };
        })(name, prop[name]) :
        prop[name];
    }
   
    // The dummy class constructor
    function Class() {
      // All construction is actually done in the init method
      if ( !initializing && this.init )
        this.init.apply(this, arguments);
    }
   
    // Populate our constructed prototype object
    Class.prototype = prototype;
   
    // Enforce the constructor to be what we expect
    Class.prototype.constructor = Class;
 
    // And make this class extendable
    Class.extend = arguments.callee;
   
    return Class;
  };
})();
/*!
 *  howler.js v2.0.15
 *  howlerjs.com
 *
 *  (c) 2013-2018, James Simpson of GoldFire Studios
 *  goldfirestudios.com
 *
 *  MIT License
 */

(function() {

  'use strict';

  /** Global Methods **/
  /***************************************************************************/

  /**
   * Create the global controller. All contained methods and properties apply
   * to all sounds that are currently playing or will be in the future.
   */
  var HowlerGlobal = function() {
    this.init();
  };
  HowlerGlobal.prototype = {
    /**
     * Initialize the global Howler object.
     * @return {Howler}
     */
    init: function() {
      var self = this || Howler;

      // Create a global ID counter.
      self._counter = 1000;

      // Internal properties.
      self._codecs = {};
      self._howls = [];
      self._muted = false;
      self._volume = 1;
      self._canPlayEvent = 'canplaythrough';
      self._navigator = (typeof window !== 'undefined' && window.navigator) ? window.navigator : null;

      // Public properties.
      self.masterGain = null;
      self.noAudio = false;
      self.usingWebAudio = true;
      self.autoSuspend = true;
      self.ctx = null;

      // Set to false to disable the auto iOS enabler.
      self.mobileAutoEnable = true;

      // Setup the various state values for global tracking.
      self._setup();

      return self;
    },

    /**
     * Get/set the global volume for all sounds.
     * @param  {Float} vol Volume from 0.0 to 1.0.
     * @return {Howler/Float}     Returns self or current volume.
     */
    volume: function(vol) {
      var self = this || Howler;
      vol = parseFloat(vol);

      // If we don't have an AudioContext created yet, run the setup.
      if (!self.ctx) {
        setupAudioContext();
      }

      if (typeof vol !== 'undefined' && vol >= 0 && vol <= 1) {
        self._volume = vol;

        // Don't update any of the nodes if we are muted.
        if (self._muted) {
          return self;
        }

        // When using Web Audio, we just need to adjust the master gain.
        if (self.usingWebAudio) {
          self.masterGain.gain.setValueAtTime(vol, Howler.ctx.currentTime);
        }

        // Loop through and change volume for all HTML5 audio nodes.
        for (var i=0; i<self._howls.length; i++) {
          if (!self._howls[i]._webAudio) {
            // Get all of the sounds in this Howl group.
            var ids = self._howls[i]._getSoundIds();

            // Loop through all sounds and change the volumes.
            for (var j=0; j<ids.length; j++) {
              var sound = self._howls[i]._soundById(ids[j]);

              if (sound && sound._node) {
                sound._node.volume = sound._volume * vol;
              }
            }
          }
        }

        return self;
      }

      return self._volume;
    },

    /**
     * Handle muting and unmuting globally.
     * @param  {Boolean} muted Is muted or not.
     */
    mute: function(muted) {
      var self = this || Howler;

      // If we don't have an AudioContext created yet, run the setup.
      if (!self.ctx) {
        setupAudioContext();
      }

      self._muted = muted;

      // With Web Audio, we just need to mute the master gain.
      if (self.usingWebAudio) {
        self.masterGain.gain.setValueAtTime(muted ? 0 : self._volume, Howler.ctx.currentTime);
      }

      // Loop through and mute all HTML5 Audio nodes.
      for (var i=0; i<self._howls.length; i++) {
        if (!self._howls[i]._webAudio) {
          // Get all of the sounds in this Howl group.
          var ids = self._howls[i]._getSoundIds();

          // Loop through all sounds and mark the audio node as muted.
          for (var j=0; j<ids.length; j++) {
            var sound = self._howls[i]._soundById(ids[j]);

            if (sound && sound._node) {
              sound._node.muted = (muted) ? true : sound._muted;
            }
          }
        }
      }

      return self;
    },

    /**
     * Unload and destroy all currently loaded Howl objects.
     * @return {Howler}
     */
    unload: function() {
      var self = this || Howler;

      for (var i=self._howls.length-1; i>=0; i--) {
        self._howls[i].unload();
      }

      // Create a new AudioContext to make sure it is fully reset.
      if (self.usingWebAudio && self.ctx && typeof self.ctx.close !== 'undefined') {
        self.ctx.close();
        self.ctx = null;
        setupAudioContext();
      }

      return self;
    },

    /**
     * Check for codec support of specific extension.
     * @param  {String} ext Audio file extention.
     * @return {Boolean}
     */
    codecs: function(ext) {
      return (this || Howler)._codecs[ext.replace(/^x-/, '')];
    },

    /**
     * Setup various state values for global tracking.
     * @return {Howler}
     */
    _setup: function() {
      var self = this || Howler;

      // Keeps track of the suspend/resume state of the AudioContext.
      self.state = self.ctx ? self.ctx.state || 'running' : 'running';

      // Automatically begin the 30-second suspend process
      self._autoSuspend();

      // Check if audio is available.
      if (!self.usingWebAudio) {
        // No audio is available on this system if noAudio is set to true.
        if (typeof Audio !== 'undefined') {
          try {
            var test = new Audio();

            // Check if the canplaythrough event is available.
            if (typeof test.oncanplaythrough === 'undefined') {
              self._canPlayEvent = 'canplay';
            }
          } catch(e) {
            self.noAudio = true;
          }
        } else {
          self.noAudio = true;
        }
      }

      // Test to make sure audio isn't disabled in Internet Explorer.
      try {
        var test = new Audio();
        if (test.muted) {
          self.noAudio = true;
        }
      } catch (e) {}

      // Check for supported codecs.
      if (!self.noAudio) {
        self._setupCodecs();
      }

      return self;
    },

    /**
     * Check for browser support for various codecs and cache the results.
     * @return {Howler}
     */
    _setupCodecs: function() {
      var self = this || Howler;
      var audioTest = null;

      // Must wrap in a try/catch because IE11 in server mode throws an error.
      try {
        audioTest = (typeof Audio !== 'undefined') ? new Audio() : null;
      } catch (err) {
        return self;
      }

      if (!audioTest || typeof audioTest.canPlayType !== 'function') {
        return self;
      }

      var mpegTest = audioTest.canPlayType('audio/mpeg;').replace(/^no$/, '');

      // Opera version <33 has mixed MP3 support, so we need to check for and block it.
      var checkOpera = self._navigator && self._navigator.userAgent.match(/OPR\/([0-6].)/g);
      var isOldOpera = (checkOpera && parseInt(checkOpera[0].split('/')[1], 10) < 33);

      self._codecs = {
        mp3: !!(!isOldOpera && (mpegTest || audioTest.canPlayType('audio/mp3;').replace(/^no$/, ''))),
        mpeg: !!mpegTest,
        opus: !!audioTest.canPlayType('audio/ogg; codecs="opus"').replace(/^no$/, ''),
        ogg: !!audioTest.canPlayType('audio/ogg; codecs="vorbis"').replace(/^no$/, ''),
        oga: !!audioTest.canPlayType('audio/ogg; codecs="vorbis"').replace(/^no$/, ''),
        wav: !!audioTest.canPlayType('audio/wav; codecs="1"').replace(/^no$/, ''),
        aac: !!audioTest.canPlayType('audio/aac;').replace(/^no$/, ''),
        caf: !!audioTest.canPlayType('audio/x-caf;').replace(/^no$/, ''),
        m4a: !!(audioTest.canPlayType('audio/x-m4a;') || audioTest.canPlayType('audio/m4a;') || audioTest.canPlayType('audio/aac;')).replace(/^no$/, ''),
        mp4: !!(audioTest.canPlayType('audio/x-mp4;') || audioTest.canPlayType('audio/mp4;') || audioTest.canPlayType('audio/aac;')).replace(/^no$/, ''),
        weba: !!audioTest.canPlayType('audio/webm; codecs="vorbis"').replace(/^no$/, ''),
        webm: !!audioTest.canPlayType('audio/webm; codecs="vorbis"').replace(/^no$/, ''),
        dolby: !!audioTest.canPlayType('audio/mp4; codecs="ec-3"').replace(/^no$/, ''),
        flac: !!(audioTest.canPlayType('audio/x-flac;') || audioTest.canPlayType('audio/flac;')).replace(/^no$/, '')
      };

      return self;
    },

    /**
     * Mobile browsers will only allow audio to be played after a user interaction.
     * Attempt to automatically unlock audio on the first user interaction.
     * Concept from: http://paulbakaus.com/tutorials/html5/web-audio-on-ios/
     * @return {Howler}
     */
    _enableMobileAudio: function() {
      var self = this || Howler;

      // Only run this on mobile devices if audio isn't already eanbled.
      var isMobile = /iPhone|iPad|iPod|Android|BlackBerry|BB10|Silk|Mobi|Chrome/i.test(self._navigator && self._navigator.userAgent);
      if (self._mobileEnabled || !self.ctx || !isMobile) {
        return;
      }

      self._mobileEnabled = false;
      self.mobileAutoEnable = false;

      // Some mobile devices/platforms have distortion issues when opening/closing tabs and/or web views.
      // Bugs in the browser (especially Mobile Safari) can cause the sampleRate to change from 44100 to 48000.
      // By calling Howler.unload(), we create a new AudioContext with the correct sampleRate.
      if (!self._mobileUnloaded && self.ctx.sampleRate !== 44100) {
        self._mobileUnloaded = true;
        self.unload();
      }

      // Scratch buffer for enabling iOS to dispose of web audio buffers correctly, as per:
      // http://stackoverflow.com/questions/24119684
      self._scratchBuffer = self.ctx.createBuffer(1, 1, 22050);

      // Call this method on touch start to create and play a buffer,
      // then check if the audio actually played to determine if
      // audio has now been unlocked on iOS, Android, etc.
      var unlock = function(e) {
        // Fix Android can not play in suspend state.
        Howler._autoResume();

        // Create an empty buffer.
        var source = self.ctx.createBufferSource();
        source.buffer = self._scratchBuffer;
        source.connect(self.ctx.destination);

        // Play the empty buffer.
        if (typeof source.start === 'undefined') {
          source.noteOn(0);
        } else {
          source.start(0);
        }

        // Calling resume() on a stack initiated by user gesture is what actually unlocks the audio on Android Chrome >= 55.
        if (typeof self.ctx.resume === 'function') {
          self.ctx.resume();
        }

        // Setup a timeout to check that we are unlocked on the next event loop.
        source.onended = function() {
          source.disconnect(0);

          // Update the unlocked state and prevent this check from happening again.
          self._mobileEnabled = true;

          // Remove the touch start listener.
          document.removeEventListener('touchstart', unlock, true);
          document.removeEventListener('touchend', unlock, true);
          document.removeEventListener('click', unlock, true);

          // Let all sounds know that audio has been unlocked.
          for (var i=0; i<self._howls.length; i++) {
            self._howls[i]._emit('unlock');
          }
        };
      };

      // Setup a touch start listener to attempt an unlock in.
      document.addEventListener('touchstart', unlock, true);
      document.addEventListener('touchend', unlock, true);
      document.addEventListener('click', unlock, true);

      return self;
    },

    /**
     * Automatically suspend the Web Audio AudioContext after no sound has played for 30 seconds.
     * This saves processing/energy and fixes various browser-specific bugs with audio getting stuck.
     * @return {Howler}
     */
    _autoSuspend: function() {
      var self = this;

      if (!self.autoSuspend || !self.ctx || typeof self.ctx.suspend === 'undefined' || !Howler.usingWebAudio) {
        return;
      }

      // Check if any sounds are playing.
      for (var i=0; i<self._howls.length; i++) {
        if (self._howls[i]._webAudio) {
          for (var j=0; j<self._howls[i]._sounds.length; j++) {
            if (!self._howls[i]._sounds[j]._paused) {
              return self;
            }
          }
        }
      }

      if (self._suspendTimer) {
        clearTimeout(self._suspendTimer);
      }

      // If no sound has played after 30 seconds, suspend the context.
      self._suspendTimer = setTimeout(function() {
        if (!self.autoSuspend) {
          return;
        }

        self._suspendTimer = null;
        self.state = 'suspending';
        self.ctx.suspend().then(function() {
          self.state = 'suspended';

          if (self._resumeAfterSuspend) {
            delete self._resumeAfterSuspend;
            self._autoResume();
          }
        });
      }, 30000);

      return self;
    },

    /**
     * Automatically resume the Web Audio AudioContext when a new sound is played.
     * @return {Howler}
     */
    _autoResume: function() {
      var self = this;

      if (!self.ctx || typeof self.ctx.resume === 'undefined' || !Howler.usingWebAudio) {
        return;
      }

      if (self.state === 'running' && self._suspendTimer) {
        clearTimeout(self._suspendTimer);
        self._suspendTimer = null;
      } else if (self.state === 'suspended') {
        self.ctx.resume().then(function() {
          self.state = 'running';

          // Emit to all Howls that the audio has resumed.
          for (var i=0; i<self._howls.length; i++) {
            self._howls[i]._emit('resume');
          }
        });

        if (self._suspendTimer) {
          clearTimeout(self._suspendTimer);
          self._suspendTimer = null;
        }
      } else if (self.state === 'suspending') {
        self._resumeAfterSuspend = true;
      }

      return self;
    }
  };

  // Setup the global audio controller.
  var Howler = new HowlerGlobal();

  /** Group Methods **/
  /***************************************************************************/

  /**
   * Create an audio group controller.
   * @param {Object} o Passed in properties for this group.
   */
  var Howl = function(o) {
    var self = this;

    // Throw an error if no source is provided.
    if (!o.src || o.src.length === 0) {
      console.error('An array of source files must be passed with any new Howl.');
      return;
    }

    self.init(o);
  };
  Howl.prototype = {
    /**
     * Initialize a new Howl group object.
     * @param  {Object} o Passed in properties for this group.
     * @return {Howl}
     */
    init: function(o) {
      var self = this;

      // If we don't have an AudioContext created yet, run the setup.
      if (!Howler.ctx) {
        setupAudioContext();
      }

      // Setup user-defined default properties.
      self._autoplay = o.autoplay || false;
      self._format = (typeof o.format !== 'string') ? o.format : [o.format];
      self._html5 = o.html5 || false;
      self._muted = o.mute || false;
      self._loop = o.loop || false;
      self._pool = o.pool || 5;
      self._preload = (typeof o.preload === 'boolean') ? o.preload : true;
      self._rate = o.rate || 1;
      self._sprite = o.sprite || {};
      self._src = (typeof o.src !== 'string') ? o.src : [o.src];
      self._volume = o.volume !== undefined ? o.volume : 1;
      self._xhrWithCredentials = o.xhrWithCredentials || false;

      // Setup all other default properties.
      self._duration = 0;
      self._state = 'unloaded';
      self._sounds = [];
      self._endTimers = {};
      self._queue = [];
      self._playLock = false;

      // Setup event listeners.
      self._onend = o.onend ? [{fn: o.onend}] : [];
      self._onfade = o.onfade ? [{fn: o.onfade}] : [];
      self._onload = o.onload ? [{fn: o.onload}] : [];
      self._onloaderror = o.onloaderror ? [{fn: o.onloaderror}] : [];
      self._onplayerror = o.onplayerror ? [{fn: o.onplayerror}] : [];
      self._onpause = o.onpause ? [{fn: o.onpause}] : [];
      self._onplay = o.onplay ? [{fn: o.onplay}] : [];
      self._onstop = o.onstop ? [{fn: o.onstop}] : [];
      self._onmute = o.onmute ? [{fn: o.onmute}] : [];
      self._onvolume = o.onvolume ? [{fn: o.onvolume}] : [];
      self._onrate = o.onrate ? [{fn: o.onrate}] : [];
      self._onseek = o.onseek ? [{fn: o.onseek}] : [];
      self._onunlock = o.onunlock ? [{fn: o.onunlock}] : [];
      self._onresume = [];

      // Web Audio or HTML5 Audio?
      self._webAudio = Howler.usingWebAudio && !self._html5;

      // Automatically try to enable audio on iOS.
      if (typeof Howler.ctx !== 'undefined' && Howler.ctx && Howler.mobileAutoEnable) {
        Howler._enableMobileAudio();
      }

      // Keep track of this Howl group in the global controller.
      Howler._howls.push(self);

      // If they selected autoplay, add a play event to the load queue.
      if (self._autoplay) {
        self._queue.push({
          event: 'play',
          action: function() {
            self.play();
          }
        });
      }

      // Load the source file unless otherwise specified.
      if (self._preload) {
        self.load();
      }

      return self;
    },

    /**
     * Load the audio file.
     * @return {Howler}
     */
    load: function() {
      var self = this;
      var url = null;

      // If no audio is available, quit immediately.
      if (Howler.noAudio) {
        self._emit('loaderror', null, 'No audio support.');
        return;
      }

      // Make sure our source is in an array.
      if (typeof self._src === 'string') {
        self._src = [self._src];
      }

      // Loop through the sources and pick the first one that is compatible.
      for (var i=0; i<self._src.length; i++) {
        var ext, str;

        if (self._format && self._format[i]) {
          // If an extension was specified, use that instead.
          ext = self._format[i];
        } else {
          // Make sure the source is a string.
          str = self._src[i];
          if (typeof str !== 'string') {
            self._emit('loaderror', null, 'Non-string found in selected audio sources - ignoring.');
            continue;
          }

          // Extract the file extension from the URL or base64 data URI.
          ext = /^data:audio\/([^;,]+);/i.exec(str);
          if (!ext) {
            ext = /\.([^.]+)$/.exec(str.split('?', 1)[0]);
          }

          if (ext) {
            ext = ext[1].toLowerCase();
          }
        }

        // Log a warning if no extension was found.
        if (!ext) {
          console.warn('No file extension was found. Consider using the "format" property or specify an extension.');
        }

        // Check if this extension is available.
        if (ext && Howler.codecs(ext)) {
          url = self._src[i];
          break;
        }
      }

      if (!url) {
        self._emit('loaderror', null, 'No codec support for selected audio sources.');
        return;
      }

      self._src = url;
      self._state = 'loading';

      // If the hosting page is HTTPS and the source isn't,
      // drop down to HTML5 Audio to avoid Mixed Content errors.
      if (window.location.protocol === 'https:' && url.slice(0, 5) === 'http:') {
        self._html5 = true;
        self._webAudio = false;
      }

      // Create a new sound object and add it to the pool.
      new Sound(self);

      // Load and decode the audio data for playback.
      if (self._webAudio) {
        loadBuffer(self);
      }

      return self;
    },

    /**
     * Play a sound or resume previous playback.
     * @param  {String/Number} sprite   Sprite name for sprite playback or sound id to continue previous.
     * @param  {Boolean} internal Internal Use: true prevents event firing.
     * @return {Number}          Sound ID.
     */
    play: function(sprite, internal) {
      var self = this;
      var id = null;

      // Determine if a sprite, sound id or nothing was passed
      if (typeof sprite === 'number') {
        id = sprite;
        sprite = null;
      } else if (typeof sprite === 'string' && self._state === 'loaded' && !self._sprite[sprite]) {
        // If the passed sprite doesn't exist, do nothing.
        return null;
      } else if (typeof sprite === 'undefined') {
        // Use the default sound sprite (plays the full audio length).
        sprite = '__default';

        // Check if there is a single paused sound that isn't ended.
        // If there is, play that sound. If not, continue as usual.
        var num = 0;
        for (var i=0; i<self._sounds.length; i++) {
          if (self._sounds[i]._paused && !self._sounds[i]._ended) {
            num++;
            id = self._sounds[i]._id;
          }
        }

        if (num === 1) {
          sprite = null;
        } else {
          id = null;
        }
      }

      // Get the selected node, or get one from the pool.
      var sound = id ? self._soundById(id) : self._inactiveSound();

      // If the sound doesn't exist, do nothing.
      if (!sound) {
        return null;
      }

      // Select the sprite definition.
      if (id && !sprite) {
        sprite = sound._sprite || '__default';
      }

      // If the sound hasn't loaded, we must wait to get the audio's duration.
      // We also need to wait to make sure we don't run into race conditions with
      // the order of function calls.
      if (self._state !== 'loaded') {
        // Set the sprite value on this sound.
        sound._sprite = sprite;

        // Makr this sounded as not ended in case another sound is played before this one loads.
        sound._ended = false;

        // Add the sound to the queue to be played on load.
        var soundId = sound._id;
        self._queue.push({
          event: 'play',
          action: function() {
            self.play(soundId);
          }
        });

        return soundId;
      }

      // Don't play the sound if an id was passed and it is already playing.
      if (id && !sound._paused) {
        // Trigger the play event, in order to keep iterating through queue.
        if (!internal) {
          self._loadQueue('play');
        }

        return sound._id;
      }

      // Make sure the AudioContext isn't suspended, and resume it if it is.
      if (self._webAudio) {
        Howler._autoResume();
      }

      // Determine how long to play for and where to start playing.
      var seek = Math.max(0, sound._seek > 0 ? sound._seek : self._sprite[sprite][0] / 1000);
      var duration = Math.max(0, ((self._sprite[sprite][0] + self._sprite[sprite][1]) / 1000) - seek);
      var timeout = (duration * 1000) / Math.abs(sound._rate);

      // Update the parameters of the sound
      sound._paused = false;
      sound._ended = false;
      sound._sprite = sprite;
      sound._seek = seek;
      sound._start = self._sprite[sprite][0] / 1000;
      sound._stop = (self._sprite[sprite][0] + self._sprite[sprite][1]) / 1000;
      sound._loop = !!(sound._loop || self._sprite[sprite][2]);

      // End the sound instantly if seek is at the end.
      if (sound._seek >= sound._stop) {
        self._ended(sound);
        return;
      }

      // Begin the actual playback.
      var node = sound._node;
      if (self._webAudio) {
        // Fire this when the sound is ready to play to begin Web Audio playback.
        var playWebAudio = function() {
          self._refreshBuffer(sound);

          // Setup the playback params.
          var vol = (sound._muted || self._muted) ? 0 : sound._volume;
          node.gain.setValueAtTime(vol, Howler.ctx.currentTime);
          sound._playStart = Howler.ctx.currentTime;

          // Play the sound using the supported method.
          if (typeof node.bufferSource.start === 'undefined') {
            sound._loop ? node.bufferSource.noteGrainOn(0, seek, 86400) : node.bufferSource.noteGrainOn(0, seek, duration);
          } else {
            sound._loop ? node.bufferSource.start(0, seek, 86400) : node.bufferSource.start(0, seek, duration);
          }

          // Start a new timer if none is present.
          if (timeout !== Infinity) {
            self._endTimers[sound._id] = setTimeout(self._ended.bind(self, sound), timeout);
          }

          if (!internal) {
            setTimeout(function() {
              self._emit('play', sound._id);
            }, 0);
          }
        };

        if (Howler.state === 'running') {
          playWebAudio();
        } else {
          self.once('resume', playWebAudio);

          // Cancel the end timer.
          self._clearTimer(sound._id);
        }
      } else {
        // Fire this when the sound is ready to play to begin HTML5 Audio playback.
        var playHtml5 = function() {
          node.currentTime = seek;
          node.muted = sound._muted || self._muted || Howler._muted || node.muted;
          node.volume = sound._volume * Howler.volume();
          node.playbackRate = sound._rate;

          // Mobile browsers will throw an error if this is called without user interaction.
          try {
            var play = node.play();

            // Support older browsers that don't support promises, and thus don't have this issue.
            if (play && typeof Promise !== 'undefined' && (play instanceof Promise || typeof play.then === 'function')) {
              // Implements a lock to prevent DOMException: The play() request was interrupted by a call to pause().
              self._playLock = true;

              // Releases the lock and executes queued actions.
              play
                .then(function() {
                  self._playLock = false;
                  if (!internal) {
                    self._emit('play', sound._id);
                  }
                })
                .catch(function() {
                  self._playLock = false;
                  self._emit('playerror', sound._id, 'Playback was unable to start. This is most commonly an issue ' +
                    'on mobile devices and Chrome where playback was not within a user interaction.');
                });
            } else if (!internal) {
              self._emit('play', sound._id);
            }

            // Setting rate before playing won't work in IE, so we set it again here.
            node.playbackRate = sound._rate;

            // If the node is still paused, then we can assume there was a playback issue.
            if (node.paused) {
              self._emit('playerror', sound._id, 'Playback was unable to start. This is most commonly an issue ' +
                'on mobile devices and Chrome where playback was not within a user interaction.');
              return;
            }

            // Setup the end timer on sprites or listen for the ended event.
            if (sprite !== '__default' || sound._loop) {
              self._endTimers[sound._id] = setTimeout(self._ended.bind(self, sound), timeout);
            } else {
              self._endTimers[sound._id] = function() {
                // Fire ended on this audio node.
                self._ended(sound);

                // Clear this listener.
                node.removeEventListener('ended', self._endTimers[sound._id], false);
              };
              node.addEventListener('ended', self._endTimers[sound._id], false);
            }
          } catch (err) {
            self._emit('playerror', sound._id, err);
          }
        };

        // Play immediately if ready, or wait for the 'canplaythrough'e vent.
        var loadedNoReadyState = (window && window.ejecta) || (!node.readyState && Howler._navigator.isCocoonJS);
        if (node.readyState >= 3 || loadedNoReadyState) {
          playHtml5();
        } else {
          var listener = function() {
            // Begin playback.
            playHtml5();

            // Clear this listener.
            node.removeEventListener(Howler._canPlayEvent, listener, false);
          };
          node.addEventListener(Howler._canPlayEvent, listener, false);

          // Cancel the end timer.
          self._clearTimer(sound._id);
        }
      }

      return sound._id;
    },

    /**
     * Pause playback and save current position.
     * @param  {Number} id The sound ID (empty to pause all in group).
     * @return {Howl}
     */
    pause: function(id) {
      var self = this;

      // If the sound hasn't loaded or a play() promise is pending, add it to the load queue to pause when capable.
      if (self._state !== 'loaded' || self._playLock) {
        self._queue.push({
          event: 'pause',
          action: function() {
            self.pause(id);
          }
        });

        return self;
      }

      // If no id is passed, get all ID's to be paused.
      var ids = self._getSoundIds(id);

      for (var i=0; i<ids.length; i++) {
        // Clear the end timer.
        self._clearTimer(ids[i]);

        // Get the sound.
        var sound = self._soundById(ids[i]);

        if (sound && !sound._paused) {
          // Reset the seek position.
          sound._seek = self.seek(ids[i]);
          sound._rateSeek = 0;
          sound._paused = true;

          // Stop currently running fades.
          self._stopFade(ids[i]);

          if (sound._node) {
            if (self._webAudio) {
              // Make sure the sound has been created.
              if (!sound._node.bufferSource) {
                continue;
              }

              if (typeof sound._node.bufferSource.stop === 'undefined') {
                sound._node.bufferSource.noteOff(0);
              } else {
                sound._node.bufferSource.stop(0);
              }

              // Clean up the buffer source.
              self._cleanBuffer(sound._node);
            } else if (!isNaN(sound._node.duration) || sound._node.duration === Infinity) {
              sound._node.pause();
            }
          }
        }

        // Fire the pause event, unless `true` is passed as the 2nd argument.
        if (!arguments[1]) {
          self._emit('pause', sound ? sound._id : null);
        }
      }

      return self;
    },

    /**
     * Stop playback and reset to start.
     * @param  {Number} id The sound ID (empty to stop all in group).
     * @param  {Boolean} internal Internal Use: true prevents event firing.
     * @return {Howl}
     */
    stop: function(id, internal) {
      var self = this;

      // If the sound hasn't loaded, add it to the load queue to stop when capable.
      if (self._state !== 'loaded' || self._playLock) {
        self._queue.push({
          event: 'stop',
          action: function() {
            self.stop(id);
          }
        });

        return self;
      }

      // If no id is passed, get all ID's to be stopped.
      var ids = self._getSoundIds(id);

      for (var i=0; i<ids.length; i++) {
        // Clear the end timer.
        self._clearTimer(ids[i]);

        // Get the sound.
        var sound = self._soundById(ids[i]);

        if (sound) {
          // Reset the seek position.
          sound._seek = sound._start || 0;
          sound._rateSeek = 0;
          sound._paused = true;
          sound._ended = true;

          // Stop currently running fades.
          self._stopFade(ids[i]);

          if (sound._node) {
            if (self._webAudio) {
              // Make sure the sound's AudioBufferSourceNode has been created.
              if (sound._node.bufferSource) {
                if (typeof sound._node.bufferSource.stop === 'undefined') {
                  sound._node.bufferSource.noteOff(0);
                } else {
                  sound._node.bufferSource.stop(0);
                }

                // Clean up the buffer source.
                self._cleanBuffer(sound._node);
              }
            } else if (!isNaN(sound._node.duration) || sound._node.duration === Infinity) {
              sound._node.currentTime = sound._start || 0;
              sound._node.pause();
            }
          }

          if (!internal) {
            self._emit('stop', sound._id);
          }
        }
      }

      return self;
    },

    /**
     * Mute/unmute a single sound or all sounds in this Howl group.
     * @param  {Boolean} muted Set to true to mute and false to unmute.
     * @param  {Number} id    The sound ID to update (omit to mute/unmute all).
     * @return {Howl}
     */
    mute: function(muted, id) {
      var self = this;

      // If the sound hasn't loaded, add it to the load queue to mute when capable.
      if (self._state !== 'loaded'|| self._playLock) {
        self._queue.push({
          event: 'mute',
          action: function() {
            self.mute(muted, id);
          }
        });

        return self;
      }

      // If applying mute/unmute to all sounds, update the group's value.
      if (typeof id === 'undefined') {
        if (typeof muted === 'boolean') {
          self._muted = muted;
        } else {
          return self._muted;
        }
      }

      // If no id is passed, get all ID's to be muted.
      var ids = self._getSoundIds(id);

      for (var i=0; i<ids.length; i++) {
        // Get the sound.
        var sound = self._soundById(ids[i]);

        if (sound) {
          sound._muted = muted;

          // Cancel active fade and set the volume to the end value.
          if (sound._interval) {
            self._stopFade(sound._id);
          }

          if (self._webAudio && sound._node) {
            sound._node.gain.setValueAtTime(muted ? 0 : sound._volume, Howler.ctx.currentTime);
          } else if (sound._node) {
            sound._node.muted = Howler._muted ? true : muted;
          }

          self._emit('mute', sound._id);
        }
      }

      return self;
    },

    /**
     * Get/set the volume of this sound or of the Howl group. This method can optionally take 0, 1 or 2 arguments.
     *   volume() -> Returns the group's volume value.
     *   volume(id) -> Returns the sound id's current volume.
     *   volume(vol) -> Sets the volume of all sounds in this Howl group.
     *   volume(vol, id) -> Sets the volume of passed sound id.
     * @return {Howl/Number} Returns self or current volume.
     */
    volume: function() {
      var self = this;
      var args = arguments;
      var vol, id;

      // Determine the values based on arguments.
      if (args.length === 0) {
        // Return the value of the groups' volume.
        return self._volume;
      } else if (args.length === 1 || args.length === 2 && typeof args[1] === 'undefined') {
        // First check if this is an ID, and if not, assume it is a new volume.
        var ids = self._getSoundIds();
        var index = ids.indexOf(args[0]);
        if (index >= 0) {
          id = parseInt(args[0], 10);
        } else {
          vol = parseFloat(args[0]);
        }
      } else if (args.length >= 2) {
        vol = parseFloat(args[0]);
        id = parseInt(args[1], 10);
      }

      // Update the volume or return the current volume.
      var sound;
      if (typeof vol !== 'undefined' && vol >= 0 && vol <= 1) {
        // If the sound hasn't loaded, add it to the load queue to change volume when capable.
        if (self._state !== 'loaded'|| self._playLock) {
          self._queue.push({
            event: 'volume',
            action: function() {
              self.volume.apply(self, args);
            }
          });

          return self;
        }

        // Set the group volume.
        if (typeof id === 'undefined') {
          self._volume = vol;
        }

        // Update one or all volumes.
        id = self._getSoundIds(id);
        for (var i=0; i<id.length; i++) {
          // Get the sound.
          sound = self._soundById(id[i]);

          if (sound) {
            sound._volume = vol;

            // Stop currently running fades.
            if (!args[2]) {
              self._stopFade(id[i]);
            }

            if (self._webAudio && sound._node && !sound._muted) {
              sound._node.gain.setValueAtTime(vol, Howler.ctx.currentTime);
            } else if (sound._node && !sound._muted) {
              sound._node.volume = vol * Howler.volume();
            }

            self._emit('volume', sound._id);
          }
        }
      } else {
        sound = id ? self._soundById(id) : self._sounds[0];
        return sound ? sound._volume : 0;
      }

      return self;
    },

    /**
     * Fade a currently playing sound between two volumes (if no id is passsed, all sounds will fade).
     * @param  {Number} from The value to fade from (0.0 to 1.0).
     * @param  {Number} to   The volume to fade to (0.0 to 1.0).
     * @param  {Number} len  Time in milliseconds to fade.
     * @param  {Number} id   The sound id (omit to fade all sounds).
     * @return {Howl}
     */
    fade: function(from, to, len, id) {
      var self = this;

      // If the sound hasn't loaded, add it to the load queue to fade when capable.
      if (self._state !== 'loaded' || self._playLock) {
        self._queue.push({
          event: 'fade',
          action: function() {
            self.fade(from, to, len, id);
          }
        });

        return self;
      }

      // Set the volume to the start position.
      self.volume(from, id);

      // Fade the volume of one or all sounds.
      var ids = self._getSoundIds(id);
      for (var i=0; i<ids.length; i++) {
        // Get the sound.
        var sound = self._soundById(ids[i]);

        // Create a linear fade or fall back to timeouts with HTML5 Audio.
        if (sound) {
          // Stop the previous fade if no sprite is being used (otherwise, volume handles this).
          if (!id) {
            self._stopFade(ids[i]);
          }

          // If we are using Web Audio, let the native methods do the actual fade.
          if (self._webAudio && !sound._muted) {
            var currentTime = Howler.ctx.currentTime;
            var end = currentTime + (len / 1000);
            sound._volume = from;
            sound._node.gain.setValueAtTime(from, currentTime);
            sound._node.gain.linearRampToValueAtTime(to, end);
          }

          self._startFadeInterval(sound, from, to, len, ids[i], typeof id === 'undefined');
        }
      }

      return self;
    },

    /**
     * Starts the internal interval to fade a sound.
     * @param  {Object} sound Reference to sound to fade.
     * @param  {Number} from The value to fade from (0.0 to 1.0).
     * @param  {Number} to   The volume to fade to (0.0 to 1.0).
     * @param  {Number} len  Time in milliseconds to fade.
     * @param  {Number} id   The sound id to fade.
     * @param  {Boolean} isGroup   If true, set the volume on the group.
     */
    _startFadeInterval: function(sound, from, to, len, id, isGroup) {
      var self = this;
      var vol = from;
      var diff = to - from;
      var steps = Math.abs(diff / 0.01);
      var stepLen = Math.max(4, (steps > 0) ? len / steps : len);
      var lastTick = Date.now();

      // Store the value being faded to.
      sound._fadeTo = to;

      // Update the volume value on each interval tick.
      sound._interval = setInterval(function() {
        // Update the volume based on the time since the last tick.
        var tick = (Date.now() - lastTick) / len;
        lastTick = Date.now();
        vol += diff * tick;

        // Make sure the volume is in the right bounds.
        vol = Math.max(0, vol);
        vol = Math.min(1, vol);

        // Round to within 2 decimal points.
        vol = Math.round(vol * 100) / 100;

        // Change the volume.
        if (self._webAudio) {
          sound._volume = vol;
        } else {
          self.volume(vol, sound._id, true);
        }

        // Set the group's volume.
        if (isGroup) {
          self._volume = vol;
        }

        // When the fade is complete, stop it and fire event.
        if ((to < from && vol <= to) || (to > from && vol >= to)) {
          clearInterval(sound._interval);
          sound._interval = null;
          sound._fadeTo = null;
          self.volume(to, sound._id);
          self._emit('fade', sound._id);
        }
      }, stepLen);
    },

    /**
     * Internal method that stops the currently playing fade when
     * a new fade starts, volume is changed or the sound is stopped.
     * @param  {Number} id The sound id.
     * @return {Howl}
     */
    _stopFade: function(id) {
      var self = this;
      var sound = self._soundById(id);

      if (sound && sound._interval) {
        if (self._webAudio) {
          sound._node.gain.cancelScheduledValues(Howler.ctx.currentTime);
        }

        clearInterval(sound._interval);
        sound._interval = null;
        self.volume(sound._fadeTo, id);
        sound._fadeTo = null;
        self._emit('fade', id);
      }

      return self;
    },

    /**
     * Get/set the loop parameter on a sound. This method can optionally take 0, 1 or 2 arguments.
     *   loop() -> Returns the group's loop value.
     *   loop(id) -> Returns the sound id's loop value.
     *   loop(loop) -> Sets the loop value for all sounds in this Howl group.
     *   loop(loop, id) -> Sets the loop value of passed sound id.
     * @return {Howl/Boolean} Returns self or current loop value.
     */
    loop: function() {
      var self = this;
      var args = arguments;
      var loop, id, sound;

      // Determine the values for loop and id.
      if (args.length === 0) {
        // Return the grou's loop value.
        return self._loop;
      } else if (args.length === 1) {
        if (typeof args[0] === 'boolean') {
          loop = args[0];
          self._loop = loop;
        } else {
          // Return this sound's loop value.
          sound = self._soundById(parseInt(args[0], 10));
          return sound ? sound._loop : false;
        }
      } else if (args.length === 2) {
        loop = args[0];
        id = parseInt(args[1], 10);
      }

      // If no id is passed, get all ID's to be looped.
      var ids = self._getSoundIds(id);
      for (var i=0; i<ids.length; i++) {
        sound = self._soundById(ids[i]);

        if (sound) {
          sound._loop = loop;
          if (self._webAudio && sound._node && sound._node.bufferSource) {
            sound._node.bufferSource.loop = loop;
            if (loop) {
              sound._node.bufferSource.loopStart = sound._start || 0;
              sound._node.bufferSource.loopEnd = sound._stop;
            }
          }
        }
      }

      return self;
    },

    /**
     * Get/set the playback rate of a sound. This method can optionally take 0, 1 or 2 arguments.
     *   rate() -> Returns the first sound node's current playback rate.
     *   rate(id) -> Returns the sound id's current playback rate.
     *   rate(rate) -> Sets the playback rate of all sounds in this Howl group.
     *   rate(rate, id) -> Sets the playback rate of passed sound id.
     * @return {Howl/Number} Returns self or the current playback rate.
     */
    rate: function() {
      var self = this;
      var args = arguments;
      var rate, id;

      // Determine the values based on arguments.
      if (args.length === 0) {
        // We will simply return the current rate of the first node.
        id = self._sounds[0]._id;
      } else if (args.length === 1) {
        // First check if this is an ID, and if not, assume it is a new rate value.
        var ids = self._getSoundIds();
        var index = ids.indexOf(args[0]);
        if (index >= 0) {
          id = parseInt(args[0], 10);
        } else {
          rate = parseFloat(args[0]);
        }
      } else if (args.length === 2) {
        rate = parseFloat(args[0]);
        id = parseInt(args[1], 10);
      }

      // Update the playback rate or return the current value.
      var sound;
      if (typeof rate === 'number') {
        // If the sound hasn't loaded, add it to the load queue to change playback rate when capable.
        if (self._state !== 'loaded' || self._playLock) {
          self._queue.push({
            event: 'rate',
            action: function() {
              self.rate.apply(self, args);
            }
          });

          return self;
        }

        // Set the group rate.
        if (typeof id === 'undefined') {
          self._rate = rate;
        }

        // Update one or all volumes.
        id = self._getSoundIds(id);
        for (var i=0; i<id.length; i++) {
          // Get the sound.
          sound = self._soundById(id[i]);

          if (sound) {
            // Keep track of our position when the rate changed and update the playback
            // start position so we can properly adjust the seek position for time elapsed.
            sound._rateSeek = self.seek(id[i]);
            sound._playStart = self._webAudio ? Howler.ctx.currentTime : sound._playStart;
            sound._rate = rate;

            // Change the playback rate.
            if (self._webAudio && sound._node && sound._node.bufferSource) {
              sound._node.bufferSource.playbackRate.setValueAtTime(rate, Howler.ctx.currentTime);
            } else if (sound._node) {
              sound._node.playbackRate = rate;
            }

            // Reset the timers.
            var seek = self.seek(id[i]);
            var duration = ((self._sprite[sound._sprite][0] + self._sprite[sound._sprite][1]) / 1000) - seek;
            var timeout = (duration * 1000) / Math.abs(sound._rate);

            // Start a new end timer if sound is already playing.
            if (self._endTimers[id[i]] || !sound._paused) {
              self._clearTimer(id[i]);
              self._endTimers[id[i]] = setTimeout(self._ended.bind(self, sound), timeout);
            }

            self._emit('rate', sound._id);
          }
        }
      } else {
        sound = self._soundById(id);
        return sound ? sound._rate : self._rate;
      }

      return self;
    },

    /**
     * Get/set the seek position of a sound. This method can optionally take 0, 1 or 2 arguments.
     *   seek() -> Returns the first sound node's current seek position.
     *   seek(id) -> Returns the sound id's current seek position.
     *   seek(seek) -> Sets the seek position of the first sound node.
     *   seek(seek, id) -> Sets the seek position of passed sound id.
     * @return {Howl/Number} Returns self or the current seek position.
     */
    seek: function() {
      var self = this;
      var args = arguments;
      var seek, id;

      // Determine the values based on arguments.
      if (args.length === 0) {
        // We will simply return the current position of the first node.
        id = self._sounds[0]._id;
      } else if (args.length === 1) {
        // First check if this is an ID, and if not, assume it is a new seek position.
        var ids = self._getSoundIds();
        var index = ids.indexOf(args[0]);
        if (index >= 0) {
          id = parseInt(args[0], 10);
        } else if (self._sounds.length) {
          id = self._sounds[0]._id;
          seek = parseFloat(args[0]);
        }
      } else if (args.length === 2) {
        seek = parseFloat(args[0]);
        id = parseInt(args[1], 10);
      }

      // If there is no ID, bail out.
      if (typeof id === 'undefined') {
        return self;
      }

      // If the sound hasn't loaded, add it to the load queue to seek when capable.
      if (self._state !== 'loaded' || self._playLock) {
        self._queue.push({
          event: 'seek',
          action: function() {
            self.seek.apply(self, args);
          }
        });

        return self;
      }

      // Get the sound.
      var sound = self._soundById(id);

      if (sound) {
        if (typeof seek === 'number' && seek >= 0) {
          // Pause the sound and update position for restarting playback.
          var playing = self.playing(id);
          if (playing) {
            self.pause(id, true);
          }

          // Move the position of the track and cancel timer.
          sound._seek = seek;
          sound._ended = false;
          self._clearTimer(id);

          // Update the seek position for HTML5 Audio.
          if (!self._webAudio && sound._node) {
            sound._node.currentTime = seek;
          }

          // Seek and emit when ready.
          var seekAndEmit = function() {
            self._emit('seek', id);

            // Restart the playback if the sound was playing.
            if (playing) {
              self.play(id, true);
            }
          };

          // Wait for the play lock to be unset before emitting (HTML5 Audio).
          if (playing && !self._webAudio) {
            var emitSeek = function() {
              if (!self._playLock) {
                seekAndEmit();
              } else {
                setTimeout(emitSeek, 0);
              }
            };
            setTimeout(emitSeek, 0);
          } else {
            seekAndEmit();
          }
        } else {
          if (self._webAudio) {
            var realTime = self.playing(id) ? Howler.ctx.currentTime - sound._playStart : 0;
            var rateSeek = sound._rateSeek ? sound._rateSeek - sound._seek : 0;
            return sound._seek + (rateSeek + realTime * Math.abs(sound._rate));
          } else {
            return sound._node.currentTime;
          }
        }
      }

      return self;
    },

    /**
     * Check if a specific sound is currently playing or not (if id is provided), or check if at least one of the sounds in the group is playing or not.
     * @param  {Number}  id The sound id to check. If none is passed, the whole sound group is checked.
     * @return {Boolean} True if playing and false if not.
     */
    playing: function(id) {
      var self = this;

      // Check the passed sound ID (if any).
      if (typeof id === 'number') {
        var sound = self._soundById(id);
        return sound ? !sound._paused : false;
      }

      // Otherwise, loop through all sounds and check if any are playing.
      for (var i=0; i<self._sounds.length; i++) {
        if (!self._sounds[i]._paused) {
          return true;
        }
      }

      return false;
    },

    /**
     * Get the duration of this sound. Passing a sound id will return the sprite duration.
     * @param  {Number} id The sound id to check. If none is passed, return full source duration.
     * @return {Number} Audio duration in seconds.
     */
    duration: function(id) {
      var self = this;
      var duration = self._duration;

      // If we pass an ID, get the sound and return the sprite length.
      var sound = self._soundById(id);
      if (sound) {
        duration = self._sprite[sound._sprite][1] / 1000;
      }

      return duration;
    },

    /**
     * Returns the current loaded state of this Howl.
     * @return {String} 'unloaded', 'loading', 'loaded'
     */
    state: function() {
      return this._state;
    },

    /**
     * Unload and destroy the current Howl object.
     * This will immediately stop all sound instances attached to this group.
     */
    unload: function() {
      var self = this;

      // Stop playing any active sounds.
      var sounds = self._sounds;
      for (var i=0; i<sounds.length; i++) {
        // Stop the sound if it is currently playing.
        if (!sounds[i]._paused) {
          self.stop(sounds[i]._id);
        }

        // Remove the source or disconnect.
        if (!self._webAudio) {
          // Set the source to 0-second silence to stop any downloading (except in IE).
          var checkIE = /MSIE |Trident\//.test(Howler._navigator && Howler._navigator.userAgent);
          if (!checkIE) {
            sounds[i]._node.src = 'data:audio/wav;base64,UklGRigAAABXQVZFZm10IBIAAAABAAEARKwAAIhYAQACABAAAABkYXRhAgAAAAEA';
          }

          // Remove any event listeners.
          sounds[i]._node.removeEventListener('error', sounds[i]._errorFn, false);
          sounds[i]._node.removeEventListener(Howler._canPlayEvent, sounds[i]._loadFn, false);
        }

        // Empty out all of the nodes.
        delete sounds[i]._node;

        // Make sure all timers are cleared out.
        self._clearTimer(sounds[i]._id);
      }

      // Remove the references in the global Howler object.
      var index = Howler._howls.indexOf(self);
      if (index >= 0) {
        Howler._howls.splice(index, 1);
      }

      // Delete this sound from the cache (if no other Howl is using it).
      var remCache = true;
      for (i=0; i<Howler._howls.length; i++) {
        if (Howler._howls[i]._src === self._src) {
          remCache = false;
          break;
        }
      }

      if (cache && remCache) {
        delete cache[self._src];
      }

      // Clear global errors.
      Howler.noAudio = false;

      // Clear out `self`.
      self._state = 'unloaded';
      self._sounds = [];
      self = null;

      return null;
    },

    /**
     * Listen to a custom event.
     * @param  {String}   event Event name.
     * @param  {Function} fn    Listener to call.
     * @param  {Number}   id    (optional) Only listen to events for this sound.
     * @param  {Number}   once  (INTERNAL) Marks event to fire only once.
     * @return {Howl}
     */
    on: function(event, fn, id, once) {
      var self = this;
      var events = self['_on' + event];

      if (typeof fn === 'function') {
        events.push(once ? {id: id, fn: fn, once: once} : {id: id, fn: fn});
      }

      return self;
    },

    /**
     * Remove a custom event. Call without parameters to remove all events.
     * @param  {String}   event Event name.
     * @param  {Function} fn    Listener to remove. Leave empty to remove all.
     * @param  {Number}   id    (optional) Only remove events for this sound.
     * @return {Howl}
     */
    off: function(event, fn, id) {
      var self = this;
      var events = self['_on' + event];
      var i = 0;

      // Allow passing just an event and ID.
      if (typeof fn === 'number') {
        id = fn;
        fn = null;
      }

      if (fn || id) {
        // Loop through event store and remove the passed function.
        for (i=0; i<events.length; i++) {
          var isId = (id === events[i].id);
          if (fn === events[i].fn && isId || !fn && isId) {
            events.splice(i, 1);
            break;
          }
        }
      } else if (event) {
        // Clear out all events of this type.
        self['_on' + event] = [];
      } else {
        // Clear out all events of every type.
        var keys = Object.keys(self);
        for (i=0; i<keys.length; i++) {
          if ((keys[i].indexOf('_on') === 0) && Array.isArray(self[keys[i]])) {
            self[keys[i]] = [];
          }
        }
      }

      return self;
    },

    /**
     * Listen to a custom event and remove it once fired.
     * @param  {String}   event Event name.
     * @param  {Function} fn    Listener to call.
     * @param  {Number}   id    (optional) Only listen to events for this sound.
     * @return {Howl}
     */
    once: function(event, fn, id) {
      var self = this;

      // Setup the event listener.
      self.on(event, fn, id, 1);

      return self;
    },

    /**
     * Emit all events of a specific type and pass the sound id.
     * @param  {String} event Event name.
     * @param  {Number} id    Sound ID.
     * @param  {Number} msg   Message to go with event.
     * @return {Howl}
     */
    _emit: function(event, id, msg) {
      var self = this;
      var events = self['_on' + event];

      // Loop through event store and fire all functions.
      for (var i=events.length-1; i>=0; i--) {
        // Only fire the listener if the correct ID is used.
        if (!events[i].id || events[i].id === id || event === 'load') {
          setTimeout(function(fn) {
            fn.call(this, id, msg);
          }.bind(self, events[i].fn), 0);

          // If this event was setup with `once`, remove it.
          if (events[i].once) {
            self.off(event, events[i].fn, events[i].id);
          }
        }
      }

      // Pass the event type into load queue so that it can continue stepping.
      self._loadQueue(event);

      return self;
    },

    /**
     * Queue of actions initiated before the sound has loaded.
     * These will be called in sequence, with the next only firing
     * after the previous has finished executing (even if async like play).
     * @return {Howl}
     */
    _loadQueue: function(event) {
      var self = this;

      if (self._queue.length > 0) {
        var task = self._queue[0];

        // Remove this task if a matching event was passed.
        if (task.event === event) {
          self._queue.shift();
          self._loadQueue();
        }

        // Run the task if no event type is passed.
        if (!event) {
          task.action();
        }
      }

      return self;
    },

    /**
     * Fired when playback ends at the end of the duration.
     * @param  {Sound} sound The sound object to work with.
     * @return {Howl}
     */
    _ended: function(sound) {
      var self = this;
      var sprite = sound._sprite;

      // If we are using IE and there was network latency we may be clipping
      // audio before it completes playing. Lets check the node to make sure it
      // believes it has completed, before ending the playback.
      if (!self._webAudio && sound._node && !sound._node.paused && !sound._node.ended && sound._node.currentTime < sound._stop) {
        setTimeout(self._ended.bind(self, sound), 100);
        return self;
      }

      // Should this sound loop?
      var loop = !!(sound._loop || self._sprite[sprite][2]);

      // Fire the ended event.
      self._emit('end', sound._id);

      // Restart the playback for HTML5 Audio loop.
      if (!self._webAudio && loop) {
        self.stop(sound._id, true).play(sound._id);
      }

      // Restart this timer if on a Web Audio loop.
      if (self._webAudio && loop) {
        self._emit('play', sound._id);
        sound._seek = sound._start || 0;
        sound._rateSeek = 0;
        sound._playStart = Howler.ctx.currentTime;

        var timeout = ((sound._stop - sound._start) * 1000) / Math.abs(sound._rate);
        self._endTimers[sound._id] = setTimeout(self._ended.bind(self, sound), timeout);
      }

      // Mark the node as paused.
      if (self._webAudio && !loop) {
        sound._paused = true;
        sound._ended = true;
        sound._seek = sound._start || 0;
        sound._rateSeek = 0;
        self._clearTimer(sound._id);

        // Clean up the buffer source.
        self._cleanBuffer(sound._node);

        // Attempt to auto-suspend AudioContext if no sounds are still playing.
        Howler._autoSuspend();
      }

      // When using a sprite, end the track.
      if (!self._webAudio && !loop) {
        self.stop(sound._id, true);
      }

      return self;
    },

    /**
     * Clear the end timer for a sound playback.
     * @param  {Number} id The sound ID.
     * @return {Howl}
     */
    _clearTimer: function(id) {
      var self = this;

      if (self._endTimers[id]) {
        // Clear the timeout or remove the ended listener.
        if (typeof self._endTimers[id] !== 'function') {
          clearTimeout(self._endTimers[id]);
        } else {
          var sound = self._soundById(id);
          if (sound && sound._node) {
            sound._node.removeEventListener('ended', self._endTimers[id], false);
          }
        }

        delete self._endTimers[id];
      }

      return self;
    },

    /**
     * Return the sound identified by this ID, or return null.
     * @param  {Number} id Sound ID
     * @return {Object}    Sound object or null.
     */
    _soundById: function(id) {
      var self = this;

      // Loop through all sounds and find the one with this ID.
      for (var i=0; i<self._sounds.length; i++) {
        if (id === self._sounds[i]._id) {
          return self._sounds[i];
        }
      }

      return null;
    },

    /**
     * Return an inactive sound from the pool or create a new one.
     * @return {Sound} Sound playback object.
     */
    _inactiveSound: function() {
      var self = this;

      self._drain();

      // Find the first inactive node to recycle.
      for (var i=0; i<self._sounds.length; i++) {
        if (self._sounds[i]._ended) {
          return self._sounds[i].reset();
        }
      }

      // If no inactive node was found, create a new one.
      return new Sound(self);
    },

    /**
     * Drain excess inactive sounds from the pool.
     */
    _drain: function() {
      var self = this;
      var limit = self._pool;
      var cnt = 0;
      var i = 0;

      // If there are less sounds than the max pool size, we are done.
      if (self._sounds.length < limit) {
        return;
      }

      // Count the number of inactive sounds.
      for (i=0; i<self._sounds.length; i++) {
        if (self._sounds[i]._ended) {
          cnt++;
        }
      }

      // Remove excess inactive sounds, going in reverse order.
      for (i=self._sounds.length - 1; i>=0; i--) {
        if (cnt <= limit) {
          return;
        }

        if (self._sounds[i]._ended) {
          // Disconnect the audio source when using Web Audio.
          if (self._webAudio && self._sounds[i]._node) {
            self._sounds[i]._node.disconnect(0);
          }

          // Remove sounds until we have the pool size.
          self._sounds.splice(i, 1);
          cnt--;
        }
      }
    },

    /**
     * Get all ID's from the sounds pool.
     * @param  {Number} id Only return one ID if one is passed.
     * @return {Array}    Array of IDs.
     */
    _getSoundIds: function(id) {
      var self = this;

      if (typeof id === 'undefined') {
        var ids = [];
        for (var i=0; i<self._sounds.length; i++) {
          ids.push(self._sounds[i]._id);
        }

        return ids;
      } else {
        return [id];
      }
    },

    /**
     * Load the sound back into the buffer source.
     * @param  {Sound} sound The sound object to work with.
     * @return {Howl}
     */
    _refreshBuffer: function(sound) {
      var self = this;

      // Setup the buffer source for playback.
      sound._node.bufferSource = Howler.ctx.createBufferSource();
      sound._node.bufferSource.buffer = cache[self._src];

      // Connect to the correct node.
      if (sound._panner) {
        sound._node.bufferSource.connect(sound._panner);
      } else {
        sound._node.bufferSource.connect(sound._node);
      }

      // Setup looping and playback rate.
      sound._node.bufferSource.loop = sound._loop;
      if (sound._loop) {
        sound._node.bufferSource.loopStart = sound._start || 0;
        sound._node.bufferSource.loopEnd = sound._stop || 0;
      }
      sound._node.bufferSource.playbackRate.setValueAtTime(sound._rate, Howler.ctx.currentTime);

      return self;
    },

    /**
     * Prevent memory leaks by cleaning up the buffer source after playback.
     * @param  {Object} node Sound's audio node containing the buffer source.
     * @return {Howl}
     */
    _cleanBuffer: function(node) {
      var self = this;

      if (Howler._scratchBuffer && node.bufferSource) {
        node.bufferSource.onended = null;
        node.bufferSource.disconnect(0);
        try { node.bufferSource.buffer = Howler._scratchBuffer; } catch(e) {}
      }
      node.bufferSource = null;

      return self;
    }
  };

  /** Single Sound Methods **/
  /***************************************************************************/

  /**
   * Setup the sound object, which each node attached to a Howl group is contained in.
   * @param {Object} howl The Howl parent group.
   */
  var Sound = function(howl) {
    this._parent = howl;
    this.init();
  };
  Sound.prototype = {
    /**
     * Initialize a new Sound object.
     * @return {Sound}
     */
    init: function() {
      var self = this;
      var parent = self._parent;

      // Setup the default parameters.
      self._muted = parent._muted;
      self._loop = parent._loop;
      self._volume = parent._volume;
      self._rate = parent._rate;
      self._seek = 0;
      self._paused = true;
      self._ended = true;
      self._sprite = '__default';

      // Generate a unique ID for this sound.
      self._id = ++Howler._counter;

      // Add itself to the parent's pool.
      parent._sounds.push(self);

      // Create the new node.
      self.create();

      return self;
    },

    /**
     * Create and setup a new sound object, whether HTML5 Audio or Web Audio.
     * @return {Sound}
     */
    create: function() {
      var self = this;
      var parent = self._parent;
      var volume = (Howler._muted || self._muted || self._parent._muted) ? 0 : self._volume;

      if (parent._webAudio) {
        // Create the gain node for controlling volume (the source will connect to this).
        self._node = (typeof Howler.ctx.createGain === 'undefined') ? Howler.ctx.createGainNode() : Howler.ctx.createGain();
        self._node.gain.setValueAtTime(volume, Howler.ctx.currentTime);
        self._node.paused = true;
        self._node.connect(Howler.masterGain);
      } else {
        self._node = new Audio();

        // Listen for errors (http://dev.w3.org/html5/spec-author-view/spec.html#mediaerror).
        self._errorFn = self._errorListener.bind(self);
        self._node.addEventListener('error', self._errorFn, false);

        // Listen for 'canplaythrough' event to let us know the sound is ready.
        self._loadFn = self._loadListener.bind(self);
        self._node.addEventListener(Howler._canPlayEvent, self._loadFn, false);

        // Setup the new audio node.
        self._node.src = parent._src;
        self._node.preload = 'auto';
        self._node.volume = volume * Howler.volume();

        // Begin loading the source.
        self._node.load();
      }

      return self;
    },

    /**
     * Reset the parameters of this sound to the original state (for recycle).
     * @return {Sound}
     */
    reset: function() {
      var self = this;
      var parent = self._parent;

      // Reset all of the parameters of this sound.
      self._muted = parent._muted;
      self._loop = parent._loop;
      self._volume = parent._volume;
      self._rate = parent._rate;
      self._seek = 0;
      self._rateSeek = 0;
      self._paused = true;
      self._ended = true;
      self._sprite = '__default';

      // Generate a new ID so that it isn't confused with the previous sound.
      self._id = ++Howler._counter;

      return self;
    },

    /**
     * HTML5 Audio error listener callback.
     */
    _errorListener: function() {
      var self = this;

      // Fire an error event and pass back the code.
      self._parent._emit('loaderror', self._id, self._node.error ? self._node.error.code : 0);

      // Clear the event listener.
      self._node.removeEventListener('error', self._errorFn, false);
    },

    /**
     * HTML5 Audio canplaythrough listener callback.
     */
    _loadListener: function() {
      var self = this;
      var parent = self._parent;

      // Round up the duration to account for the lower precision in HTML5 Audio.
      parent._duration = Math.ceil(self._node.duration * 10) / 10;

      // Setup a sprite if none is defined.
      if (Object.keys(parent._sprite).length === 0) {
        parent._sprite = {__default: [0, parent._duration * 1000]};
      }

      if (parent._state !== 'loaded') {
        parent._state = 'loaded';
        parent._emit('load');
        parent._loadQueue();
      }

      // Clear the event listener.
      self._node.removeEventListener(Howler._canPlayEvent, self._loadFn, false);
    }
  };

  /** Helper Methods **/
  /***************************************************************************/

  var cache = {};

  /**
   * Buffer a sound from URL, Data URI or cache and decode to audio source (Web Audio API).
   * @param  {Howl} self
   */
  var loadBuffer = function(self) {
    var url = self._src;

    // Check if the buffer has already been cached and use it instead.
    if (cache[url]) {
      // Set the duration from the cache.
      self._duration = cache[url].duration;

      // Load the sound into this Howl.
      loadSound(self);

      return;
    }

    if (/^data:[^;]+;base64,/.test(url)) {
      // Decode the base64 data URI without XHR, since some browsers don't support it.
      var data = atob(url.split(',')[1]);
      var dataView = new Uint8Array(data.length);
      for (var i=0; i<data.length; ++i) {
        dataView[i] = data.charCodeAt(i);
      }

      decodeAudioData(dataView.buffer, self);
    } else {
      // Load the buffer from the URL.
      var xhr = new XMLHttpRequest();
      xhr.open('GET', url, true);
      xhr.withCredentials = self._xhrWithCredentials;
      xhr.responseType = 'arraybuffer';
      xhr.onload = function() {
        // Make sure we get a successful response back.
        var code = (xhr.status + '')[0];
        if (code !== '0' && code !== '2' && code !== '3') {
          self._emit('loaderror', null, 'Failed loading audio file with status: ' + xhr.status + '.');
          return;
        }

        decodeAudioData(xhr.response, self);
      };
      xhr.onerror = function() {
        // If there is an error, switch to HTML5 Audio.
        if (self._webAudio) {
          self._html5 = true;
          self._webAudio = false;
          self._sounds = [];
          delete cache[url];
          self.load();
        }
      };
      safeXhrSend(xhr);
    }
  };

  /**
   * Send the XHR request wrapped in a try/catch.
   * @param  {Object} xhr XHR to send.
   */
  var safeXhrSend = function(xhr) {
    try {
      xhr.send();
    } catch (e) {
      xhr.onerror();
    }
  };

  /**
   * Decode audio data from an array buffer.
   * @param  {ArrayBuffer} arraybuffer The audio data.
   * @param  {Howl}        self
   */
  var decodeAudioData = function(arraybuffer, self) {
    // Fire a load error if something broke.
    var error = function() {
      self._emit('loaderror', null, 'Decoding audio data failed.');
    };

    // Load the sound on success.
    var success = function(buffer) {
      if (buffer && self._sounds.length > 0) {
        cache[self._src] = buffer;
        loadSound(self, buffer);
      } else {
        error();
      }
    };

    // Decode the buffer into an audio source.
    if (typeof Promise !== 'undefined' && Howler.ctx.decodeAudioData.length === 1) {
      Howler.ctx.decodeAudioData(arraybuffer).then(success).catch(error);
    } else {
      Howler.ctx.decodeAudioData(arraybuffer, success, error);
    }
  }

  /**
   * Sound is now loaded, so finish setting everything up and fire the loaded event.
   * @param  {Howl} self
   * @param  {Object} buffer The decoded buffer sound source.
   */
  var loadSound = function(self, buffer) {
    // Set the duration.
    if (buffer && !self._duration) {
      self._duration = buffer.duration;
    }

    // Setup a sprite if none is defined.
    if (Object.keys(self._sprite).length === 0) {
      self._sprite = {__default: [0, self._duration * 1000]};
    }

    // Fire the loaded event.
    if (self._state !== 'loaded') {
      self._state = 'loaded';
      self._emit('load');
      self._loadQueue();
    }
  };

  /**
   * Setup the audio context when available, or switch to HTML5 Audio mode.
   */
  var setupAudioContext = function() {
    // Check if we are using Web Audio and setup the AudioContext if we are.
    try {
      if (typeof AudioContext !== 'undefined') {
        Howler.ctx = new AudioContext();
      } else if (typeof webkitAudioContext !== 'undefined') {
        Howler.ctx = new webkitAudioContext();
      } else {
        Howler.usingWebAudio = false;
      }
    } catch(e) {
      Howler.usingWebAudio = false;
    }

    // Check if a webview is being used on iOS8 or earlier (rather than the browser).
    // If it is, disable Web Audio as it causes crashing.
    var iOS = (/iP(hone|od|ad)/.test(Howler._navigator && Howler._navigator.platform));
    var appVersion = Howler._navigator && Howler._navigator.appVersion.match(/OS (\d+)_(\d+)_?(\d+)?/);
    var version = appVersion ? parseInt(appVersion[1], 10) : null;
    if (iOS && version && version < 9) {
      var safari = /safari/.test(Howler._navigator && Howler._navigator.userAgent.toLowerCase());
      if (Howler._navigator && Howler._navigator.standalone && !safari || Howler._navigator && !Howler._navigator.standalone && !safari) {
        Howler.usingWebAudio = false;
      }
    }

    // Create and expose the master GainNode when using Web Audio (useful for plugins or advanced usage).
    if (Howler.usingWebAudio) {
      Howler.masterGain = (typeof Howler.ctx.createGain === 'undefined') ? Howler.ctx.createGainNode() : Howler.ctx.createGain();
      Howler.masterGain.gain.setValueAtTime(Howler._muted ? 0 : 1, Howler.ctx.currentTime);
      Howler.masterGain.connect(Howler.ctx.destination);
    }

    // Re-run the setup on Howler.
    Howler._setup();
  };

  // Add support for AMD (Asynchronous Module Definition) libraries such as require.js.
  if (typeof define === 'function' && define.amd) {
    define([], function() {
      return {
        Howler: Howler,
        Howl: Howl
      };
    });
  }

  // Add support for CommonJS libraries such as browserify.
  if (typeof exports !== 'undefined') {
    exports.Howler = Howler;
    exports.Howl = Howl;
  }

  // Define globally in case AMD is not available or unused.
  if (typeof window !== 'undefined') {
    window.HowlerGlobal = HowlerGlobal;
    window.Howler = Howler;
    window.Howl = Howl;
    window.Sound = Sound;
  } else if (typeof global !== 'undefined') { // Add to global in Node.js (for testing, etc).
    global.HowlerGlobal = HowlerGlobal;
    global.Howler = Howler;
    global.Howl = Howl;
    global.Sound = Sound;
  }
})();


/*!
 *  Spatial Plugin - Adds support for stereo and 3D audio where Web Audio is supported.
 *  
 *  howler.js v2.0.15
 *  howlerjs.com
 *
 *  (c) 2013-2018, James Simpson of GoldFire Studios
 *  goldfirestudios.com
 *
 *  MIT License
 */

(function() {

  'use strict';

  // Setup default properties.
  HowlerGlobal.prototype._pos = [0, 0, 0];
  HowlerGlobal.prototype._orientation = [0, 0, -1, 0, 1, 0];

  /** Global Methods **/
  /***************************************************************************/

  /**
   * Helper method to update the stereo panning position of all current Howls.
   * Future Howls will not use this value unless explicitly set.
   * @param  {Number} pan A value of -1.0 is all the way left and 1.0 is all the way right.
   * @return {Howler/Number}     Self or current stereo panning value.
   */
  HowlerGlobal.prototype.stereo = function(pan) {
    var self = this;

    // Stop right here if not using Web Audio.
    if (!self.ctx || !self.ctx.listener) {
      return self;
    }

    // Loop through all Howls and update their stereo panning.
    for (var i=self._howls.length-1; i>=0; i--) {
      self._howls[i].stereo(pan);
    }

    return self;
  };

  /**
   * Get/set the position of the listener in 3D cartesian space. Sounds using
   * 3D position will be relative to the listener's position.
   * @param  {Number} x The x-position of the listener.
   * @param  {Number} y The y-position of the listener.
   * @param  {Number} z The z-position of the listener.
   * @return {Howler/Array}   Self or current listener position.
   */
  HowlerGlobal.prototype.pos = function(x, y, z) {
    var self = this;

    // Stop right here if not using Web Audio.
    if (!self.ctx || !self.ctx.listener) {
      return self;
    }

    // Set the defaults for optional 'y' & 'z'.
    y = (typeof y !== 'number') ? self._pos[1] : y;
    z = (typeof z !== 'number') ? self._pos[2] : z;

    if (typeof x === 'number') {
      self._pos = [x, y, z];

      if (typeof self.ctx.listener.positionX !== 'undefined') {
        self.ctx.listener.positionX.setTargetAtTime(self._pos[0], Howler.ctx.currentTime, 0.1);
        self.ctx.listener.positionY.setTargetAtTime(self._pos[1], Howler.ctx.currentTime, 0.1);
        self.ctx.listener.positionZ.setTargetAtTime(self._pos[2], Howler.ctx.currentTime, 0.1);
      } else {
        self.ctx.listener.setPosition(self._pos[0], self._pos[1], self._pos[2]);
      }
    } else {
      return self._pos;
    }

    return self;
  };

  /**
   * Get/set the direction the listener is pointing in the 3D cartesian space.
   * A front and up vector must be provided. The front is the direction the
   * face of the listener is pointing, and up is the direction the top of the
   * listener is pointing. Thus, these values are expected to be at right angles
   * from each other.
   * @param  {Number} x   The x-orientation of the listener.
   * @param  {Number} y   The y-orientation of the listener.
   * @param  {Number} z   The z-orientation of the listener.
   * @param  {Number} xUp The x-orientation of the top of the listener.
   * @param  {Number} yUp The y-orientation of the top of the listener.
   * @param  {Number} zUp The z-orientation of the top of the listener.
   * @return {Howler/Array}     Returns self or the current orientation vectors.
   */
  HowlerGlobal.prototype.orientation = function(x, y, z, xUp, yUp, zUp) {
    var self = this;

    // Stop right here if not using Web Audio.
    if (!self.ctx || !self.ctx.listener) {
      return self;
    }

    // Set the defaults for optional 'y' & 'z'.
    var or = self._orientation;
    y = (typeof y !== 'number') ? or[1] : y;
    z = (typeof z !== 'number') ? or[2] : z;
    xUp = (typeof xUp !== 'number') ? or[3] : xUp;
    yUp = (typeof yUp !== 'number') ? or[4] : yUp;
    zUp = (typeof zUp !== 'number') ? or[5] : zUp;

    if (typeof x === 'number') {
      self._orientation = [x, y, z, xUp, yUp, zUp];

      if (typeof self.ctx.listener.forwardX !== 'undefined') {
        self.ctx.listener.forwardX.setTargetAtTime(x, Howler.ctx.currentTime, 0.1);
        self.ctx.listener.forwardY.setTargetAtTime(y, Howler.ctx.currentTime, 0.1);
        self.ctx.listener.forwardZ.setTargetAtTime(z, Howler.ctx.currentTime, 0.1);
        self.ctx.listener.upX.setTargetAtTime(x, Howler.ctx.currentTime, 0.1);
        self.ctx.listener.upY.setTargetAtTime(y, Howler.ctx.currentTime, 0.1);
        self.ctx.listener.upZ.setTargetAtTime(z, Howler.ctx.currentTime, 0.1);
      } else {
        self.ctx.listener.setOrientation(x, y, z, xUp, yUp, zUp);
      }
    } else {
      return or;
    }

    return self;
  };

  /** Group Methods **/
  /***************************************************************************/

  /**
   * Add new properties to the core init.
   * @param  {Function} _super Core init method.
   * @return {Howl}
   */
  Howl.prototype.init = (function(_super) {
    return function(o) {
      var self = this;

      // Setup user-defined default properties.
      self._orientation = o.orientation || [1, 0, 0];
      self._stereo = o.stereo || null;
      self._pos = o.pos || null;
      self._pannerAttr = {
        coneInnerAngle: typeof o.coneInnerAngle !== 'undefined' ? o.coneInnerAngle : 360,
        coneOuterAngle: typeof o.coneOuterAngle !== 'undefined' ? o.coneOuterAngle : 360,
        coneOuterGain: typeof o.coneOuterGain !== 'undefined' ? o.coneOuterGain : 0,
        distanceModel: typeof o.distanceModel !== 'undefined' ? o.distanceModel : 'inverse',
        maxDistance: typeof o.maxDistance !== 'undefined' ? o.maxDistance : 10000,
        panningModel: typeof o.panningModel !== 'undefined' ? o.panningModel : 'HRTF',
        refDistance: typeof o.refDistance !== 'undefined' ? o.refDistance : 1,
        rolloffFactor: typeof o.rolloffFactor !== 'undefined' ? o.rolloffFactor : 1
      };

      // Setup event listeners.
      self._onstereo = o.onstereo ? [{fn: o.onstereo}] : [];
      self._onpos = o.onpos ? [{fn: o.onpos}] : [];
      self._onorientation = o.onorientation ? [{fn: o.onorientation}] : [];

      // Complete initilization with howler.js core's init function.
      return _super.call(this, o);
    };
  })(Howl.prototype.init);

  /**
   * Get/set the stereo panning of the audio source for this sound or all in the group.
   * @param  {Number} pan  A value of -1.0 is all the way left and 1.0 is all the way right.
   * @param  {Number} id (optional) The sound ID. If none is passed, all in group will be updated.
   * @return {Howl/Number}    Returns self or the current stereo panning value.
   */
  Howl.prototype.stereo = function(pan, id) {
    var self = this;

    // Stop right here if not using Web Audio.
    if (!self._webAudio) {
      return self;
    }

    // If the sound hasn't loaded, add it to the load queue to change stereo pan when capable.
    if (self._state !== 'loaded') {
      self._queue.push({
        event: 'stereo',
        action: function() {
          self.stereo(pan, id);
        }
      });

      return self;
    }

    // Check for PannerStereoNode support and fallback to PannerNode if it doesn't exist.
    var pannerType = (typeof Howler.ctx.createStereoPanner === 'undefined') ? 'spatial' : 'stereo';

    // Setup the group's stereo panning if no ID is passed.
    if (typeof id === 'undefined') {
      // Return the group's stereo panning if no parameters are passed.
      if (typeof pan === 'number') {
        self._stereo = pan;
        self._pos = [pan, 0, 0];
      } else {
        return self._stereo;
      }
    }

    // Change the streo panning of one or all sounds in group.
    var ids = self._getSoundIds(id);
    for (var i=0; i<ids.length; i++) {
      // Get the sound.
      var sound = self._soundById(ids[i]);

      if (sound) {
        if (typeof pan === 'number') {
          sound._stereo = pan;
          sound._pos = [pan, 0, 0];

          if (sound._node) {
            // If we are falling back, make sure the panningModel is equalpower.
            sound._pannerAttr.panningModel = 'equalpower';

            // Check if there is a panner setup and create a new one if not.
            if (!sound._panner || !sound._panner.pan) {
              setupPanner(sound, pannerType);
            }

            if (pannerType === 'spatial') {
              if (typeof sound._panner.positionX !== 'undefined') {
                sound._panner.positionX.setValueAtTime(pan, Howler.ctx.currentTime);
                sound._panner.positionY.setValueAtTime(0, Howler.ctx.currentTime);
                sound._panner.positionZ.setValueAtTime(0, Howler.ctx.currentTime);
              } else {
                sound._panner.setPosition(pan, 0, 0);
              }
            } else {
              sound._panner.pan.setValueAtTime(pan, Howler.ctx.currentTime);
            }
          }

          self._emit('stereo', sound._id);
        } else {
          return sound._stereo;
        }
      }
    }

    return self;
  };

  /**
   * Get/set the 3D spatial position of the audio source for this sound or group relative to the global listener.
   * @param  {Number} x  The x-position of the audio source.
   * @param  {Number} y  The y-position of the audio source.
   * @param  {Number} z  The z-position of the audio source.
   * @param  {Number} id (optional) The sound ID. If none is passed, all in group will be updated.
   * @return {Howl/Array}    Returns self or the current 3D spatial position: [x, y, z].
   */
  Howl.prototype.pos = function(x, y, z, id) {
    var self = this;

    // Stop right here if not using Web Audio.
    if (!self._webAudio) {
      return self;
    }

    // If the sound hasn't loaded, add it to the load queue to change position when capable.
    if (self._state !== 'loaded') {
      self._queue.push({
        event: 'pos',
        action: function() {
          self.pos(x, y, z, id);
        }
      });

      return self;
    }

    // Set the defaults for optional 'y' & 'z'.
    y = (typeof y !== 'number') ? 0 : y;
    z = (typeof z !== 'number') ? -0.5 : z;

    // Setup the group's spatial position if no ID is passed.
    if (typeof id === 'undefined') {
      // Return the group's spatial position if no parameters are passed.
      if (typeof x === 'number') {
        self._pos = [x, y, z];
      } else {
        return self._pos;
      }
    }

    // Change the spatial position of one or all sounds in group.
    var ids = self._getSoundIds(id);
    for (var i=0; i<ids.length; i++) {
      // Get the sound.
      var sound = self._soundById(ids[i]);

      if (sound) {
        if (typeof x === 'number') {
          sound._pos = [x, y, z];

          if (sound._node) {
            // Check if there is a panner setup and create a new one if not.
            if (!sound._panner || sound._panner.pan) {
              setupPanner(sound, 'spatial');
            }

            if (typeof sound._panner.positionX !== 'undefined') {
              sound._panner.positionX.setValueAtTime(x, Howler.ctx.currentTime);
              sound._panner.positionY.setValueAtTime(y, Howler.ctx.currentTime);
              sound._panner.positionZ.setValueAtTime(z, Howler.ctx.currentTime);
            } else {
              sound._panner.setOrientation(x, y, z);
            }
          }

          self._emit('pos', sound._id);
        } else {
          return sound._pos;
        }
      }
    }

    return self;
  };

  /**
   * Get/set the direction the audio source is pointing in the 3D cartesian coordinate
   * space. Depending on how direction the sound is, based on the `cone` attributes,
   * a sound pointing away from the listener can be quiet or silent.
   * @param  {Number} x  The x-orientation of the source.
   * @param  {Number} y  The y-orientation of the source.
   * @param  {Number} z  The z-orientation of the source.
   * @param  {Number} id (optional) The sound ID. If none is passed, all in group will be updated.
   * @return {Howl/Array}    Returns self or the current 3D spatial orientation: [x, y, z].
   */
  Howl.prototype.orientation = function(x, y, z, id) {
    var self = this;

    // Stop right here if not using Web Audio.
    if (!self._webAudio) {
      return self;
    }

    // If the sound hasn't loaded, add it to the load queue to change orientation when capable.
    if (self._state !== 'loaded') {
      self._queue.push({
        event: 'orientation',
        action: function() {
          self.orientation(x, y, z, id);
        }
      });

      return self;
    }

    // Set the defaults for optional 'y' & 'z'.
    y = (typeof y !== 'number') ? self._orientation[1] : y;
    z = (typeof z !== 'number') ? self._orientation[2] : z;

    // Setup the group's spatial orientation if no ID is passed.
    if (typeof id === 'undefined') {
      // Return the group's spatial orientation if no parameters are passed.
      if (typeof x === 'number') {
        self._orientation = [x, y, z];
      } else {
        return self._orientation;
      }
    }

    // Change the spatial orientation of one or all sounds in group.
    var ids = self._getSoundIds(id);
    for (var i=0; i<ids.length; i++) {
      // Get the sound.
      var sound = self._soundById(ids[i]);

      if (sound) {
        if (typeof x === 'number') {
          sound._orientation = [x, y, z];

          if (sound._node) {
            // Check if there is a panner setup and create a new one if not.
            if (!sound._panner) {
              // Make sure we have a position to setup the node with.
              if (!sound._pos) {
                sound._pos = self._pos || [0, 0, -0.5];
              }

              setupPanner(sound, 'spatial');
            }

            if (typeof sound._panner.orientationX !== 'undefined') {
              sound._panner.orientationX.setValueAtTime(x, Howler.ctx.currentTime);
              sound._panner.orientationY.setValueAtTime(y, Howler.ctx.currentTime);
              sound._panner.orientationZ.setValueAtTime(z, Howler.ctx.currentTime);
            } else {
              sound._panner.setOrientation(x, y, z);
            }
          }

          self._emit('orientation', sound._id);
        } else {
          return sound._orientation;
        }
      }
    }

    return self;
  };

  /**
   * Get/set the panner node's attributes for a sound or group of sounds.
   * This method can optionall take 0, 1 or 2 arguments.
   *   pannerAttr() -> Returns the group's values.
   *   pannerAttr(id) -> Returns the sound id's values.
   *   pannerAttr(o) -> Set's the values of all sounds in this Howl group.
   *   pannerAttr(o, id) -> Set's the values of passed sound id.
   *
   *   Attributes:
   *     coneInnerAngle - (360 by default) A parameter for directional audio sources, this is an angle, in degrees,
   *                      inside of which there will be no volume reduction.
   *     coneOuterAngle - (360 by default) A parameter for directional audio sources, this is an angle, in degrees,
   *                      outside of which the volume will be reduced to a constant value of `coneOuterGain`.
   *     coneOuterGain - (0 by default) A parameter for directional audio sources, this is the gain outside of the
   *                     `coneOuterAngle`. It is a linear value in the range `[0, 1]`.
   *     distanceModel - ('inverse' by default) Determines algorithm used to reduce volume as audio moves away from
   *                     listener. Can be `linear`, `inverse` or `exponential.
   *     maxDistance - (10000 by default) The maximum distance between source and listener, after which the volume
   *                   will not be reduced any further.
   *     refDistance - (1 by default) A reference distance for reducing volume as source moves further from the listener.
   *                   This is simply a variable of the distance model and has a different effect depending on which model
   *                   is used and the scale of your coordinates. Generally, volume will be equal to 1 at this distance.
   *     rolloffFactor - (1 by default) How quickly the volume reduces as source moves from listener. This is simply a
   *                     variable of the distance model and can be in the range of `[0, 1]` with `linear` and `[0, ∞]`
   *                     with `inverse` and `exponential`.
   *     panningModel - ('HRTF' by default) Determines which spatialization algorithm is used to position audio.
   *                     Can be `HRTF` or `equalpower`.
   *
   * @return {Howl/Object} Returns self or current panner attributes.
   */
  Howl.prototype.pannerAttr = function() {
    var self = this;
    var args = arguments;
    var o, id, sound;

    // Stop right here if not using Web Audio.
    if (!self._webAudio) {
      return self;
    }

    // Determine the values based on arguments.
    if (args.length === 0) {
      // Return the group's panner attribute values.
      return self._pannerAttr;
    } else if (args.length === 1) {
      if (typeof args[0] === 'object') {
        o = args[0];

        // Set the grou's panner attribute values.
        if (typeof id === 'undefined') {
          if (!o.pannerAttr) {
            o.pannerAttr = {
              coneInnerAngle: o.coneInnerAngle,
              coneOuterAngle: o.coneOuterAngle,
              coneOuterGain: o.coneOuterGain,
              distanceModel: o.distanceModel,
              maxDistance: o.maxDistance,
              refDistance: o.refDistance,
              rolloffFactor: o.rolloffFactor,
              panningModel: o.panningModel
            };
          }

          self._pannerAttr = {
            coneInnerAngle: typeof o.pannerAttr.coneInnerAngle !== 'undefined' ? o.pannerAttr.coneInnerAngle : self._coneInnerAngle,
            coneOuterAngle: typeof o.pannerAttr.coneOuterAngle !== 'undefined' ? o.pannerAttr.coneOuterAngle : self._coneOuterAngle,
            coneOuterGain: typeof o.pannerAttr.coneOuterGain !== 'undefined' ? o.pannerAttr.coneOuterGain : self._coneOuterGain,
            distanceModel: typeof o.pannerAttr.distanceModel !== 'undefined' ? o.pannerAttr.distanceModel : self._distanceModel,
            maxDistance: typeof o.pannerAttr.maxDistance !== 'undefined' ? o.pannerAttr.maxDistance : self._maxDistance,
            refDistance: typeof o.pannerAttr.refDistance !== 'undefined' ? o.pannerAttr.refDistance : self._refDistance,
            rolloffFactor: typeof o.pannerAttr.rolloffFactor !== 'undefined' ? o.pannerAttr.rolloffFactor : self._rolloffFactor,
            panningModel: typeof o.pannerAttr.panningModel !== 'undefined' ? o.pannerAttr.panningModel : self._panningModel
          };
        }
      } else {
        // Return this sound's panner attribute values.
        sound = self._soundById(parseInt(args[0], 10));
        return sound ? sound._pannerAttr : self._pannerAttr;
      }
    } else if (args.length === 2) {
      o = args[0];
      id = parseInt(args[1], 10);
    }

    // Update the values of the specified sounds.
    var ids = self._getSoundIds(id);
    for (var i=0; i<ids.length; i++) {
      sound = self._soundById(ids[i]);

      if (sound) {
        // Merge the new values into the sound.
        var pa = sound._pannerAttr;
        pa = {
          coneInnerAngle: typeof o.coneInnerAngle !== 'undefined' ? o.coneInnerAngle : pa.coneInnerAngle,
          coneOuterAngle: typeof o.coneOuterAngle !== 'undefined' ? o.coneOuterAngle : pa.coneOuterAngle,
          coneOuterGain: typeof o.coneOuterGain !== 'undefined' ? o.coneOuterGain : pa.coneOuterGain,
          distanceModel: typeof o.distanceModel !== 'undefined' ? o.distanceModel : pa.distanceModel,
          maxDistance: typeof o.maxDistance !== 'undefined' ? o.maxDistance : pa.maxDistance,
          refDistance: typeof o.refDistance !== 'undefined' ? o.refDistance : pa.refDistance,
          rolloffFactor: typeof o.rolloffFactor !== 'undefined' ? o.rolloffFactor : pa.rolloffFactor,
          panningModel: typeof o.panningModel !== 'undefined' ? o.panningModel : pa.panningModel
        };

        // Update the panner values or create a new panner if none exists.
        var panner = sound._panner;
        if (panner) {
          panner.coneInnerAngle = pa.coneInnerAngle;
          panner.coneOuterAngle = pa.coneOuterAngle;
          panner.coneOuterGain = pa.coneOuterGain;
          panner.distanceModel = pa.distanceModel;
          panner.maxDistance = pa.maxDistance;
          panner.refDistance = pa.refDistance;
          panner.rolloffFactor = pa.rolloffFactor;
          panner.panningModel = pa.panningModel;
        } else {
          // Make sure we have a position to setup the node with.
          if (!sound._pos) {
            sound._pos = self._pos || [0, 0, -0.5];
          }

          // Create a new panner node.
          setupPanner(sound, 'spatial');
        }
      }
    }

    return self;
  };

  /** Single Sound Methods **/
  /***************************************************************************/

  /**
   * Add new properties to the core Sound init.
   * @param  {Function} _super Core Sound init method.
   * @return {Sound}
   */
  Sound.prototype.init = (function(_super) {
    return function() {
      var self = this;
      var parent = self._parent;

      // Setup user-defined default properties.
      self._orientation = parent._orientation;
      self._stereo = parent._stereo;
      self._pos = parent._pos;
      self._pannerAttr = parent._pannerAttr;

      // Complete initilization with howler.js core Sound's init function.
      _super.call(this);

      // If a stereo or position was specified, set it up.
      if (self._stereo) {
        parent.stereo(self._stereo);
      } else if (self._pos) {
        parent.pos(self._pos[0], self._pos[1], self._pos[2], self._id);
      }
    };
  })(Sound.prototype.init);

  /**
   * Override the Sound.reset method to clean up properties from the spatial plugin.
   * @param  {Function} _super Sound reset method.
   * @return {Sound}
   */
  Sound.prototype.reset = (function(_super) {
    return function() {
      var self = this;
      var parent = self._parent;

      // Reset all spatial plugin properties on this sound.
      self._orientation = parent._orientation;
      self._stereo = parent._stereo;
      self._pos = parent._pos;
      self._pannerAttr = parent._pannerAttr;

      // If a stereo or position was specified, set it up.
      if (self._stereo) {
        parent.stereo(self._stereo);
      } else if (self._pos) {
        parent.pos(self._pos[0], self._pos[1], self._pos[2], self._id);
      } else if (self._panner) {
        // Disconnect the panner.
        self._panner.disconnect(0);
        self._panner = undefined;
        parent._refreshBuffer(self);
      }

      // Complete resetting of the sound.
      return _super.call(this);
    };
  })(Sound.prototype.reset);

  /** Helper Methods **/
  /***************************************************************************/

  /**
   * Create a new panner node and save it on the sound.
   * @param  {Sound} sound Specific sound to setup panning on.
   * @param {String} type Type of panner to create: 'stereo' or 'spatial'.
   */
  var setupPanner = function(sound, type) {
    type = type || 'spatial';

    // Create the new panner node.
    if (type === 'spatial') {
      sound._panner = Howler.ctx.createPanner();
      sound._panner.coneInnerAngle = sound._pannerAttr.coneInnerAngle;
      sound._panner.coneOuterAngle = sound._pannerAttr.coneOuterAngle;
      sound._panner.coneOuterGain = sound._pannerAttr.coneOuterGain;
      sound._panner.distanceModel = sound._pannerAttr.distanceModel;
      sound._panner.maxDistance = sound._pannerAttr.maxDistance;
      sound._panner.refDistance = sound._pannerAttr.refDistance;
      sound._panner.rolloffFactor = sound._pannerAttr.rolloffFactor;
      sound._panner.panningModel = sound._pannerAttr.panningModel;

      if (typeof sound._panner.positionX !== 'undefined') {
        sound._panner.positionX.setValueAtTime(sound._pos[0], Howler.ctx.currentTime);
        sound._panner.positionY.setValueAtTime(sound._pos[1], Howler.ctx.currentTime);
        sound._panner.positionZ.setValueAtTime(sound._pos[2], Howler.ctx.currentTime);
      } else {
        sound._panner.setPosition(sound._pos[0], sound._pos[1], sound._pos[2]);
      }

      if (typeof sound._panner.orientationX !== 'undefined') {
        sound._panner.orientationX.setValueAtTime(sound._orientation[0], Howler.ctx.currentTime);
        sound._panner.orientationY.setValueAtTime(sound._orientation[1], Howler.ctx.currentTime);
        sound._panner.orientationZ.setValueAtTime(sound._orientation[2], Howler.ctx.currentTime);
      } else {
        sound._panner.setOrientation(sound._orientation[0], sound._orientation[1], sound._orientation[2]);
      }
    } else {
      sound._panner = Howler.ctx.createStereoPanner();
      sound._panner.pan.setValueAtTime(sound._stereo, Howler.ctx.currentTime);
    }

    sound._panner.connect(sound._node);

    // Update the connections.
    if (!sound._paused) {
      sound._parent.pause(sound._id, true).play(sound._id, true);
    }
  };
})();
/*! js-cookie v3.0.1 | MIT */
!function(e,t){"object"==typeof exports&&"undefined"!=typeof module?module.exports=t():"function"==typeof define&&define.amd?define(t):(e=e||self,function(){var n=e.Cookies,o=e.Cookies=t();o.noConflict=function(){return e.Cookies=n,o}}())}(this,(function(){"use strict";function e(e){for(var t=1;t<arguments.length;t++){var n=arguments[t];for(var o in n)e[o]=n[o]}return e}return function t(n,o){function r(t,r,i){if("undefined"!=typeof document){"number"==typeof(i=e({},o,i)).expires&&(i.expires=new Date(Date.now()+864e5*i.expires)),i.expires&&(i.expires=i.expires.toUTCString()),t=encodeURIComponent(t).replace(/%(2[346B]|5E|60|7C)/g,decodeURIComponent).replace(/[()]/g,escape);var c="";for(var u in i)i[u]&&(c+="; "+u,!0!==i[u]&&(c+="="+i[u].split(";")[0]));return document.cookie=t+"="+n.write(r,t)+c}}return Object.create({set:r,get:function(e){if("undefined"!=typeof document&&(!arguments.length||e)){for(var t=document.cookie?document.cookie.split("; "):[],o={},r=0;r<t.length;r++){var i=t[r].split("="),c=i.slice(1).join("=");try{var u=decodeURIComponent(i[0]);if(o[u]=n.read(c,u),e===u)break}catch(e){}}return e?o[e]:o}},remove:function(t,n){r(t,"",e({},n,{expires:-1}))},withAttributes:function(n){return t(this.converter,e({},this.attributes,n))},withConverter:function(n){return t(e({},this.converter,n),this.attributes)}},{attributes:{value:Object.freeze(o)},converter:{value:Object.freeze(n)}})}({read:function(e){return'"'===e[0]&&(e=e.slice(1,-1)),e.replace(/(%[\dA-F]{2})+/gi,decodeURIComponent)},write:function(e){return encodeURIComponent(e).replace(/%(2[346BF]|3[AC-F]|40|5[BDE]|60|7[BCD])/g,decodeURIComponent)}},{path:"/"})}));
/*! Pickr 1.8.2 MIT | https://github.com/Simonwep/pickr */
!function(t,e){"object"==typeof exports&&"object"==typeof module?module.exports=e():"function"==typeof define&&define.amd?define([],e):"object"==typeof exports?exports.Pickr=e():t.Pickr=e()}(self,(function(){return(()=>{var t={3099:t=>{t.exports=function(t){if("function"!=typeof t)throw TypeError(String(t)+" is not a function");return t}},6077:(t,e,r)=>{var n=r(111);t.exports=function(t){if(!n(t)&&null!==t)throw TypeError("Can't set "+String(t)+" as a prototype");return t}},1223:(t,e,r)=>{var n=r(5112),o=r(30),i=r(3070),a=n("unscopables"),c=Array.prototype;null==c[a]&&i.f(c,a,{configurable:!0,value:o(null)}),t.exports=function(t){c[a][t]=!0}},1530:(t,e,r)=>{"use strict";var n=r(8710).charAt;t.exports=function(t,e,r){return e+(r?n(t,e).length:1)}},9670:(t,e,r)=>{var n=r(111);t.exports=function(t){if(!n(t))throw TypeError(String(t)+" is not an object");return t}},8533:(t,e,r)=>{"use strict";var n=r(2092).forEach,o=r(9341)("forEach");t.exports=o?[].forEach:function(t){return n(this,t,arguments.length>1?arguments[1]:void 0)}},8457:(t,e,r)=>{"use strict";var n=r(9974),o=r(7908),i=r(3411),a=r(7659),c=r(7466),s=r(6135),u=r(1246);t.exports=function(t){var e,r,l,p,f,v,h=o(t),d="function"==typeof this?this:Array,g=arguments.length,y=g>1?arguments[1]:void 0,b=void 0!==y,m=u(h),x=0;if(b&&(y=n(y,g>2?arguments[2]:void 0,2)),null==m||d==Array&&a(m))for(r=new d(e=c(h.length));e>x;x++)v=b?y(h[x],x):h[x],s(r,x,v);else for(f=(p=m.call(h)).next,r=new d;!(l=f.call(p)).done;x++)v=b?i(p,y,[l.value,x],!0):l.value,s(r,x,v);return r.length=x,r}},1318:(t,e,r)=>{var n=r(5656),o=r(7466),i=r(1400),a=function(t){return function(e,r,a){var c,s=n(e),u=o(s.length),l=i(a,u);if(t&&r!=r){for(;u>l;)if((c=s[l++])!=c)return!0}else for(;u>l;l++)if((t||l in s)&&s[l]===r)return t||l||0;return!t&&-1}};t.exports={includes:a(!0),indexOf:a(!1)}},2092:(t,e,r)=>{var n=r(9974),o=r(8361),i=r(7908),a=r(7466),c=r(5417),s=[].push,u=function(t){var e=1==t,r=2==t,u=3==t,l=4==t,p=6==t,f=7==t,v=5==t||p;return function(h,d,g,y){for(var b,m,x=i(h),w=o(x),S=n(d,g,3),O=a(w.length),_=0,A=y||c,j=e?A(h,O):r||f?A(h,0):void 0;O>_;_++)if((v||_ in w)&&(m=S(b=w[_],_,x),t))if(e)j[_]=m;else if(m)switch(t){case 3:return!0;case 5:return b;case 6:return _;case 2:s.call(j,b)}else switch(t){case 4:return!1;case 7:s.call(j,b)}return p?-1:u||l?l:j}};t.exports={forEach:u(0),map:u(1),filter:u(2),some:u(3),every:u(4),find:u(5),findIndex:u(6),filterOut:u(7)}},1194:(t,e,r)=>{var n=r(7293),o=r(5112),i=r(7392),a=o("species");t.exports=function(t){return i>=51||!n((function(){var e=[];return(e.constructor={})[a]=function(){return{foo:1}},1!==e[t](Boolean).foo}))}},9341:(t,e,r)=>{"use strict";var n=r(7293);t.exports=function(t,e){var r=[][t];return!!r&&n((function(){r.call(null,e||function(){throw 1},1)}))}},5417:(t,e,r)=>{var n=r(111),o=r(3157),i=r(5112)("species");t.exports=function(t,e){var r;return o(t)&&("function"!=typeof(r=t.constructor)||r!==Array&&!o(r.prototype)?n(r)&&null===(r=r[i])&&(r=void 0):r=void 0),new(void 0===r?Array:r)(0===e?0:e)}},3411:(t,e,r)=>{var n=r(9670),o=r(9212);t.exports=function(t,e,r,i){try{return i?e(n(r)[0],r[1]):e(r)}catch(e){throw o(t),e}}},7072:(t,e,r)=>{var n=r(5112)("iterator"),o=!1;try{var i=0,a={next:function(){return{done:!!i++}},return:function(){o=!0}};a[n]=function(){return this},Array.from(a,(function(){throw 2}))}catch(t){}t.exports=function(t,e){if(!e&&!o)return!1;var r=!1;try{var i={};i[n]=function(){return{next:function(){return{done:r=!0}}}},t(i)}catch(t){}return r}},4326:t=>{var e={}.toString;t.exports=function(t){return e.call(t).slice(8,-1)}},648:(t,e,r)=>{var n=r(1694),o=r(4326),i=r(5112)("toStringTag"),a="Arguments"==o(function(){return arguments}());t.exports=n?o:function(t){var e,r,n;return void 0===t?"Undefined":null===t?"Null":"string"==typeof(r=function(t,e){try{return t[e]}catch(t){}}(e=Object(t),i))?r:a?o(e):"Object"==(n=o(e))&&"function"==typeof e.callee?"Arguments":n}},9920:(t,e,r)=>{var n=r(6656),o=r(3887),i=r(1236),a=r(3070);t.exports=function(t,e){for(var r=o(e),c=a.f,s=i.f,u=0;u<r.length;u++){var l=r[u];n(t,l)||c(t,l,s(e,l))}}},4964:(t,e,r)=>{var n=r(5112)("match");t.exports=function(t){var e=/./;try{"/./"[t](e)}catch(r){try{return e[n]=!1,"/./"[t](e)}catch(t){}}return!1}},8544:(t,e,r)=>{var n=r(7293);t.exports=!n((function(){function t(){}return t.prototype.constructor=null,Object.getPrototypeOf(new t)!==t.prototype}))},4994:(t,e,r)=>{"use strict";var n=r(3383).IteratorPrototype,o=r(30),i=r(9114),a=r(8003),c=r(7497),s=function(){return this};t.exports=function(t,e,r){var u=e+" Iterator";return t.prototype=o(n,{next:i(1,r)}),a(t,u,!1,!0),c[u]=s,t}},8880:(t,e,r)=>{var n=r(9781),o=r(3070),i=r(9114);t.exports=n?function(t,e,r){return o.f(t,e,i(1,r))}:function(t,e,r){return t[e]=r,t}},9114:t=>{t.exports=function(t,e){return{enumerable:!(1&t),configurable:!(2&t),writable:!(4&t),value:e}}},6135:(t,e,r)=>{"use strict";var n=r(7593),o=r(3070),i=r(9114);t.exports=function(t,e,r){var a=n(e);a in t?o.f(t,a,i(0,r)):t[a]=r}},654:(t,e,r)=>{"use strict";var n=r(2109),o=r(4994),i=r(9518),a=r(7674),c=r(8003),s=r(8880),u=r(1320),l=r(5112),p=r(1913),f=r(7497),v=r(3383),h=v.IteratorPrototype,d=v.BUGGY_SAFARI_ITERATORS,g=l("iterator"),y="keys",b="values",m="entries",x=function(){return this};t.exports=function(t,e,r,l,v,w,S){o(r,e,l);var O,_,A,j=function(t){if(t===v&&I)return I;if(!d&&t in k)return k[t];switch(t){case y:case b:case m:return function(){return new r(this,t)}}return function(){return new r(this)}},E=e+" Iterator",P=!1,k=t.prototype,C=k[g]||k["@@iterator"]||v&&k[v],I=!d&&C||j(v),T="Array"==e&&k.entries||C;if(T&&(O=i(T.call(new t)),h!==Object.prototype&&O.next&&(p||i(O)===h||(a?a(O,h):"function"!=typeof O[g]&&s(O,g,x)),c(O,E,!0,!0),p&&(f[E]=x))),v==b&&C&&C.name!==b&&(P=!0,I=function(){return C.call(this)}),p&&!S||k[g]===I||s(k,g,I),f[e]=I,v)if(_={values:j(b),keys:w?I:j(y),entries:j(m)},S)for(A in _)(d||P||!(A in k))&&u(k,A,_[A]);else n({target:e,proto:!0,forced:d||P},_);return _}},7235:(t,e,r)=>{var n=r(857),o=r(6656),i=r(6061),a=r(3070).f;t.exports=function(t){var e=n.Symbol||(n.Symbol={});o(e,t)||a(e,t,{value:i.f(t)})}},9781:(t,e,r)=>{var n=r(7293);t.exports=!n((function(){return 7!=Object.defineProperty({},1,{get:function(){return 7}})[1]}))},317:(t,e,r)=>{var n=r(7854),o=r(111),i=n.document,a=o(i)&&o(i.createElement);t.exports=function(t){return a?i.createElement(t):{}}},8324:t=>{t.exports={CSSRuleList:0,CSSStyleDeclaration:0,CSSValueList:0,ClientRectList:0,DOMRectList:0,DOMStringList:0,DOMTokenList:1,DataTransferItemList:0,FileList:0,HTMLAllCollection:0,HTMLCollection:0,HTMLFormElement:0,HTMLSelectElement:0,MediaList:0,MimeTypeArray:0,NamedNodeMap:0,NodeList:1,PaintRequestList:0,Plugin:0,PluginArray:0,SVGLengthList:0,SVGNumberList:0,SVGPathSegList:0,SVGPointList:0,SVGStringList:0,SVGTransformList:0,SourceBufferList:0,StyleSheetList:0,TextTrackCueList:0,TextTrackList:0,TouchList:0}},8113:(t,e,r)=>{var n=r(5005);t.exports=n("navigator","userAgent")||""},7392:(t,e,r)=>{var n,o,i=r(7854),a=r(8113),c=i.process,s=c&&c.versions,u=s&&s.v8;u?o=(n=u.split("."))[0]<4?1:n[0]+n[1]:a&&(!(n=a.match(/Edge\/(\d+)/))||n[1]>=74)&&(n=a.match(/Chrome\/(\d+)/))&&(o=n[1]),t.exports=o&&+o},748:t=>{t.exports=["constructor","hasOwnProperty","isPrototypeOf","propertyIsEnumerable","toLocaleString","toString","valueOf"]},2109:(t,e,r)=>{var n=r(7854),o=r(1236).f,i=r(8880),a=r(1320),c=r(3505),s=r(9920),u=r(4705);t.exports=function(t,e){var r,l,p,f,v,h=t.target,d=t.global,g=t.stat;if(r=d?n:g?n[h]||c(h,{}):(n[h]||{}).prototype)for(l in e){if(f=e[l],p=t.noTargetGet?(v=o(r,l))&&v.value:r[l],!u(d?l:h+(g?".":"#")+l,t.forced)&&void 0!==p){if(typeof f==typeof p)continue;s(f,p)}(t.sham||p&&p.sham)&&i(f,"sham",!0),a(r,l,f,t)}}},7293:t=>{t.exports=function(t){try{return!!t()}catch(t){return!0}}},7007:(t,e,r)=>{"use strict";r(4916);var n=r(1320),o=r(2261),i=r(7293),a=r(5112),c=r(8880),s=a("species"),u=RegExp.prototype;t.exports=function(t,e,r,l){var p=a(t),f=!i((function(){var e={};return e[p]=function(){return 7},7!=""[t](e)})),v=f&&!i((function(){var e=!1,r=/a/;return"split"===t&&((r={}).constructor={},r.constructor[s]=function(){return r},r.flags="",r[p]=/./[p]),r.exec=function(){return e=!0,null},r[p](""),!e}));if(!f||!v||r){var h=/./[p],d=e(p,""[t],(function(t,e,r,n,i){var a=e.exec;return a===o||a===u.exec?f&&!i?{done:!0,value:h.call(e,r,n)}:{done:!0,value:t.call(r,e,n)}:{done:!1}}));n(String.prototype,t,d[0]),n(u,p,d[1])}l&&c(u[p],"sham",!0)}},9974:(t,e,r)=>{var n=r(3099);t.exports=function(t,e,r){if(n(t),void 0===e)return t;switch(r){case 0:return function(){return t.call(e)};case 1:return function(r){return t.call(e,r)};case 2:return function(r,n){return t.call(e,r,n)};case 3:return function(r,n,o){return t.call(e,r,n,o)}}return function(){return t.apply(e,arguments)}}},5005:(t,e,r)=>{var n=r(857),o=r(7854),i=function(t){return"function"==typeof t?t:void 0};t.exports=function(t,e){return arguments.length<2?i(n[t])||i(o[t]):n[t]&&n[t][e]||o[t]&&o[t][e]}},1246:(t,e,r)=>{var n=r(648),o=r(7497),i=r(5112)("iterator");t.exports=function(t){if(null!=t)return t[i]||t["@@iterator"]||o[n(t)]}},647:(t,e,r)=>{var n=r(7908),o=Math.floor,i="".replace,a=/\$([$&'`]|\d{1,2}|<[^>]*>)/g,c=/\$([$&'`]|\d{1,2})/g;t.exports=function(t,e,r,s,u,l){var p=r+t.length,f=s.length,v=c;return void 0!==u&&(u=n(u),v=a),i.call(l,v,(function(n,i){var a;switch(i.charAt(0)){case"$":return"$";case"&":return t;case"`":return e.slice(0,r);case"'":return e.slice(p);case"<":a=u[i.slice(1,-1)];break;default:var c=+i;if(0===c)return n;if(c>f){var l=o(c/10);return 0===l?n:l<=f?void 0===s[l-1]?i.charAt(1):s[l-1]+i.charAt(1):n}a=s[c-1]}return void 0===a?"":a}))}},7854:(t,e,r)=>{var n=function(t){return t&&t.Math==Math&&t};t.exports=n("object"==typeof globalThis&&globalThis)||n("object"==typeof window&&window)||n("object"==typeof self&&self)||n("object"==typeof r.g&&r.g)||function(){return this}()||Function("return this")()},6656:(t,e,r)=>{var n=r(7908),o={}.hasOwnProperty;t.exports=Object.hasOwn||function(t,e){return o.call(n(t),e)}},3501:t=>{t.exports={}},490:(t,e,r)=>{var n=r(5005);t.exports=n("document","documentElement")},4664:(t,e,r)=>{var n=r(9781),o=r(7293),i=r(317);t.exports=!n&&!o((function(){return 7!=Object.defineProperty(i("div"),"a",{get:function(){return 7}}).a}))},8361:(t,e,r)=>{var n=r(7293),o=r(4326),i="".split;t.exports=n((function(){return!Object("z").propertyIsEnumerable(0)}))?function(t){return"String"==o(t)?i.call(t,""):Object(t)}:Object},9587:(t,e,r)=>{var n=r(111),o=r(7674);t.exports=function(t,e,r){var i,a;return o&&"function"==typeof(i=e.constructor)&&i!==r&&n(a=i.prototype)&&a!==r.prototype&&o(t,a),t}},2788:(t,e,r)=>{var n=r(5465),o=Function.toString;"function"!=typeof n.inspectSource&&(n.inspectSource=function(t){return o.call(t)}),t.exports=n.inspectSource},9909:(t,e,r)=>{var n,o,i,a=r(8536),c=r(7854),s=r(111),u=r(8880),l=r(6656),p=r(5465),f=r(6200),v=r(3501),h="Object already initialized",d=c.WeakMap;if(a||p.state){var g=p.state||(p.state=new d),y=g.get,b=g.has,m=g.set;n=function(t,e){if(b.call(g,t))throw new TypeError(h);return e.facade=t,m.call(g,t,e),e},o=function(t){return y.call(g,t)||{}},i=function(t){return b.call(g,t)}}else{var x=f("state");v[x]=!0,n=function(t,e){if(l(t,x))throw new TypeError(h);return e.facade=t,u(t,x,e),e},o=function(t){return l(t,x)?t[x]:{}},i=function(t){return l(t,x)}}t.exports={set:n,get:o,has:i,enforce:function(t){return i(t)?o(t):n(t,{})},getterFor:function(t){return function(e){var r;if(!s(e)||(r=o(e)).type!==t)throw TypeError("Incompatible receiver, "+t+" required");return r}}}},7659:(t,e,r)=>{var n=r(5112),o=r(7497),i=n("iterator"),a=Array.prototype;t.exports=function(t){return void 0!==t&&(o.Array===t||a[i]===t)}},3157:(t,e,r)=>{var n=r(4326);t.exports=Array.isArray||function(t){return"Array"==n(t)}},4705:(t,e,r)=>{var n=r(7293),o=/#|\.prototype\./,i=function(t,e){var r=c[a(t)];return r==u||r!=s&&("function"==typeof e?n(e):!!e)},a=i.normalize=function(t){return String(t).replace(o,".").toLowerCase()},c=i.data={},s=i.NATIVE="N",u=i.POLYFILL="P";t.exports=i},111:t=>{t.exports=function(t){return"object"==typeof t?null!==t:"function"==typeof t}},1913:t=>{t.exports=!1},7850:(t,e,r)=>{var n=r(111),o=r(4326),i=r(5112)("match");t.exports=function(t){var e;return n(t)&&(void 0!==(e=t[i])?!!e:"RegExp"==o(t))}},9212:(t,e,r)=>{var n=r(9670);t.exports=function(t){var e=t.return;if(void 0!==e)return n(e.call(t)).value}},3383:(t,e,r)=>{"use strict";var n,o,i,a=r(7293),c=r(9518),s=r(8880),u=r(6656),l=r(5112),p=r(1913),f=l("iterator"),v=!1;[].keys&&("next"in(i=[].keys())?(o=c(c(i)))!==Object.prototype&&(n=o):v=!0);var h=null==n||a((function(){var t={};return n[f].call(t)!==t}));h&&(n={}),p&&!h||u(n,f)||s(n,f,(function(){return this})),t.exports={IteratorPrototype:n,BUGGY_SAFARI_ITERATORS:v}},7497:t=>{t.exports={}},133:(t,e,r)=>{var n=r(7392),o=r(7293);t.exports=!!Object.getOwnPropertySymbols&&!o((function(){var t=Symbol();return!String(t)||!(Object(t)instanceof Symbol)||!Symbol.sham&&n&&n<41}))},8536:(t,e,r)=>{var n=r(7854),o=r(2788),i=n.WeakMap;t.exports="function"==typeof i&&/native code/.test(o(i))},3929:(t,e,r)=>{var n=r(7850);t.exports=function(t){if(n(t))throw TypeError("The method doesn't accept regular expressions");return t}},1574:(t,e,r)=>{"use strict";var n=r(9781),o=r(7293),i=r(1956),a=r(5181),c=r(5296),s=r(7908),u=r(8361),l=Object.assign,p=Object.defineProperty;t.exports=!l||o((function(){if(n&&1!==l({b:1},l(p({},"a",{enumerable:!0,get:function(){p(this,"b",{value:3,enumerable:!1})}}),{b:2})).b)return!0;var t={},e={},r=Symbol(),o="abcdefghijklmnopqrst";return t[r]=7,o.split("").forEach((function(t){e[t]=t})),7!=l({},t)[r]||i(l({},e)).join("")!=o}))?function(t,e){for(var r=s(t),o=arguments.length,l=1,p=a.f,f=c.f;o>l;)for(var v,h=u(arguments[l++]),d=p?i(h).concat(p(h)):i(h),g=d.length,y=0;g>y;)v=d[y++],n&&!f.call(h,v)||(r[v]=h[v]);return r}:l},30:(t,e,r)=>{var n,o=r(9670),i=r(6048),a=r(748),c=r(3501),s=r(490),u=r(317),l=r(6200),p=l("IE_PROTO"),f=function(){},v=function(t){return"<script>"+t+"</"+"script>"},h=function(){try{n=document.domain&&new ActiveXObject("htmlfile")}catch(t){}var t,e;h=n?function(t){t.write(v("")),t.close();var e=t.parentWindow.Object;return t=null,e}(n):((e=u("iframe")).style.display="none",s.appendChild(e),e.src=String("javascript:"),(t=e.contentWindow.document).open(),t.write(v("document.F=Object")),t.close(),t.F);for(var r=a.length;r--;)delete h.prototype[a[r]];return h()};c[p]=!0,t.exports=Object.create||function(t,e){var r;return null!==t?(f.prototype=o(t),r=new f,f.prototype=null,r[p]=t):r=h(),void 0===e?r:i(r,e)}},6048:(t,e,r)=>{var n=r(9781),o=r(3070),i=r(9670),a=r(1956);t.exports=n?Object.defineProperties:function(t,e){i(t);for(var r,n=a(e),c=n.length,s=0;c>s;)o.f(t,r=n[s++],e[r]);return t}},3070:(t,e,r)=>{var n=r(9781),o=r(4664),i=r(9670),a=r(7593),c=Object.defineProperty;e.f=n?c:function(t,e,r){if(i(t),e=a(e,!0),i(r),o)try{return c(t,e,r)}catch(t){}if("get"in r||"set"in r)throw TypeError("Accessors not supported");return"value"in r&&(t[e]=r.value),t}},1236:(t,e,r)=>{var n=r(9781),o=r(5296),i=r(9114),a=r(5656),c=r(7593),s=r(6656),u=r(4664),l=Object.getOwnPropertyDescriptor;e.f=n?l:function(t,e){if(t=a(t),e=c(e,!0),u)try{return l(t,e)}catch(t){}if(s(t,e))return i(!o.f.call(t,e),t[e])}},1156:(t,e,r)=>{var n=r(5656),o=r(8006).f,i={}.toString,a="object"==typeof window&&window&&Object.getOwnPropertyNames?Object.getOwnPropertyNames(window):[];t.exports.f=function(t){return a&&"[object Window]"==i.call(t)?function(t){try{return o(t)}catch(t){return a.slice()}}(t):o(n(t))}},8006:(t,e,r)=>{var n=r(6324),o=r(748).concat("length","prototype");e.f=Object.getOwnPropertyNames||function(t){return n(t,o)}},5181:(t,e)=>{e.f=Object.getOwnPropertySymbols},9518:(t,e,r)=>{var n=r(6656),o=r(7908),i=r(6200),a=r(8544),c=i("IE_PROTO"),s=Object.prototype;t.exports=a?Object.getPrototypeOf:function(t){return t=o(t),n(t,c)?t[c]:"function"==typeof t.constructor&&t instanceof t.constructor?t.constructor.prototype:t instanceof Object?s:null}},6324:(t,e,r)=>{var n=r(6656),o=r(5656),i=r(1318).indexOf,a=r(3501);t.exports=function(t,e){var r,c=o(t),s=0,u=[];for(r in c)!n(a,r)&&n(c,r)&&u.push(r);for(;e.length>s;)n(c,r=e[s++])&&(~i(u,r)||u.push(r));return u}},1956:(t,e,r)=>{var n=r(6324),o=r(748);t.exports=Object.keys||function(t){return n(t,o)}},5296:(t,e)=>{"use strict";var r={}.propertyIsEnumerable,n=Object.getOwnPropertyDescriptor,o=n&&!r.call({1:2},1);e.f=o?function(t){var e=n(this,t);return!!e&&e.enumerable}:r},7674:(t,e,r)=>{var n=r(9670),o=r(6077);t.exports=Object.setPrototypeOf||("__proto__"in{}?function(){var t,e=!1,r={};try{(t=Object.getOwnPropertyDescriptor(Object.prototype,"__proto__").set).call(r,[]),e=r instanceof Array}catch(t){}return function(r,i){return n(r),o(i),e?t.call(r,i):r.__proto__=i,r}}():void 0)},288:(t,e,r)=>{"use strict";var n=r(1694),o=r(648);t.exports=n?{}.toString:function(){return"[object "+o(this)+"]"}},3887:(t,e,r)=>{var n=r(5005),o=r(8006),i=r(5181),a=r(9670);t.exports=n("Reflect","ownKeys")||function(t){var e=o.f(a(t)),r=i.f;return r?e.concat(r(t)):e}},857:(t,e,r)=>{var n=r(7854);t.exports=n},1320:(t,e,r)=>{var n=r(7854),o=r(8880),i=r(6656),a=r(3505),c=r(2788),s=r(9909),u=s.get,l=s.enforce,p=String(String).split("String");(t.exports=function(t,e,r,c){var s,u=!!c&&!!c.unsafe,f=!!c&&!!c.enumerable,v=!!c&&!!c.noTargetGet;"function"==typeof r&&("string"!=typeof e||i(r,"name")||o(r,"name",e),(s=l(r)).source||(s.source=p.join("string"==typeof e?e:""))),t!==n?(u?!v&&t[e]&&(f=!0):delete t[e],f?t[e]=r:o(t,e,r)):f?t[e]=r:a(e,r)})(Function.prototype,"toString",(function(){return"function"==typeof this&&u(this).source||c(this)}))},7651:(t,e,r)=>{var n=r(4326),o=r(2261);t.exports=function(t,e){var r=t.exec;if("function"==typeof r){var i=r.call(t,e);if("object"!=typeof i)throw TypeError("RegExp exec method returned something other than an Object or null");return i}if("RegExp"!==n(t))throw TypeError("RegExp#exec called on incompatible receiver");return o.call(t,e)}},2261:(t,e,r)=>{"use strict";var n,o,i=r(7066),a=r(2999),c=r(2309),s=r(30),u=r(9909).get,l=r(9441),p=r(8173),f=RegExp.prototype.exec,v=c("native-string-replace",String.prototype.replace),h=f,d=(n=/a/,o=/b*/g,f.call(n,"a"),f.call(o,"a"),0!==n.lastIndex||0!==o.lastIndex),g=a.UNSUPPORTED_Y||a.BROKEN_CARET,y=void 0!==/()??/.exec("")[1];(d||y||g||l||p)&&(h=function(t){var e,r,n,o,a,c,l,p=this,b=u(p),m=b.raw;if(m)return m.lastIndex=p.lastIndex,e=h.call(m,t),p.lastIndex=m.lastIndex,e;var x=b.groups,w=g&&p.sticky,S=i.call(p),O=p.source,_=0,A=t;if(w&&(-1===(S=S.replace("y","")).indexOf("g")&&(S+="g"),A=String(t).slice(p.lastIndex),p.lastIndex>0&&(!p.multiline||p.multiline&&"\n"!==t[p.lastIndex-1])&&(O="(?: "+O+")",A=" "+A,_++),r=new RegExp("^(?:"+O+")",S)),y&&(r=new RegExp("^"+O+"$(?!\\s)",S)),d&&(n=p.lastIndex),o=f.call(w?r:p,A),w?o?(o.input=o.input.slice(_),o[0]=o[0].slice(_),o.index=p.lastIndex,p.lastIndex+=o[0].length):p.lastIndex=0:d&&o&&(p.lastIndex=p.global?o.index+o[0].length:n),y&&o&&o.length>1&&v.call(o[0],r,(function(){for(a=1;a<arguments.length-2;a++)void 0===arguments[a]&&(o[a]=void 0)})),o&&x)for(o.groups=c=s(null),a=0;a<x.length;a++)c[(l=x[a])[0]]=o[l[1]];return o}),t.exports=h},7066:(t,e,r)=>{"use strict";var n=r(9670);t.exports=function(){var t=n(this),e="";return t.global&&(e+="g"),t.ignoreCase&&(e+="i"),t.multiline&&(e+="m"),t.dotAll&&(e+="s"),t.unicode&&(e+="u"),t.sticky&&(e+="y"),e}},2999:(t,e,r)=>{var n=r(7293),o=function(t,e){return RegExp(t,e)};e.UNSUPPORTED_Y=n((function(){var t=o("a","y");return t.lastIndex=2,null!=t.exec("abcd")})),e.BROKEN_CARET=n((function(){var t=o("^r","gy");return t.lastIndex=2,null!=t.exec("str")}))},9441:(t,e,r)=>{var n=r(7293);t.exports=n((function(){var t=RegExp(".","string".charAt(0));return!(t.dotAll&&t.exec("\n")&&"s"===t.flags)}))},8173:(t,e,r)=>{var n=r(7293);t.exports=n((function(){var t=RegExp("(?<a>b)","string".charAt(5));return"b"!==t.exec("b").groups.a||"bc"!=="b".replace(t,"$<a>c")}))},4488:t=>{t.exports=function(t){if(null==t)throw TypeError("Can't call method on "+t);return t}},3505:(t,e,r)=>{var n=r(7854),o=r(8880);t.exports=function(t,e){try{o(n,t,e)}catch(r){n[t]=e}return e}},8003:(t,e,r)=>{var n=r(3070).f,o=r(6656),i=r(5112)("toStringTag");t.exports=function(t,e,r){t&&!o(t=r?t:t.prototype,i)&&n(t,i,{configurable:!0,value:e})}},6200:(t,e,r)=>{var n=r(2309),o=r(9711),i=n("keys");t.exports=function(t){return i[t]||(i[t]=o(t))}},5465:(t,e,r)=>{var n=r(7854),o=r(3505),i="__core-js_shared__",a=n[i]||o(i,{});t.exports=a},2309:(t,e,r)=>{var n=r(1913),o=r(5465);(t.exports=function(t,e){return o[t]||(o[t]=void 0!==e?e:{})})("versions",[]).push({version:"3.15.1",mode:n?"pure":"global",copyright:"© 2021 Denis Pushkarev (zloirock.ru)"})},6707:(t,e,r)=>{var n=r(9670),o=r(3099),i=r(5112)("species");t.exports=function(t,e){var r,a=n(t).constructor;return void 0===a||null==(r=n(a)[i])?e:o(r)}},8710:(t,e,r)=>{var n=r(9958),o=r(4488),i=function(t){return function(e,r){var i,a,c=String(o(e)),s=n(r),u=c.length;return s<0||s>=u?t?"":void 0:(i=c.charCodeAt(s))<55296||i>56319||s+1===u||(a=c.charCodeAt(s+1))<56320||a>57343?t?c.charAt(s):i:t?c.slice(s,s+2):a-56320+(i-55296<<10)+65536}};t.exports={codeAt:i(!1),charAt:i(!0)}},4986:(t,e,r)=>{var n=r(8113);t.exports=/Version\/10(?:\.\d+){1,2}(?: [\w./]+)?(?: Mobile\/\w+)? Safari\//.test(n)},6650:(t,e,r)=>{var n=r(7466),o=r(8415),i=r(4488),a=Math.ceil,c=function(t){return function(e,r,c){var s,u,l=String(i(e)),p=l.length,f=void 0===c?" ":String(c),v=n(r);return v<=p||""==f?l:(s=v-p,(u=o.call(f,a(s/f.length))).length>s&&(u=u.slice(0,s)),t?l+u:u+l)}};t.exports={start:c(!1),end:c(!0)}},8415:(t,e,r)=>{"use strict";var n=r(9958),o=r(4488);t.exports=function(t){var e=String(o(this)),r="",i=n(t);if(i<0||i==1/0)throw RangeError("Wrong number of repetitions");for(;i>0;(i>>>=1)&&(e+=e))1&i&&(r+=e);return r}},6091:(t,e,r)=>{var n=r(7293),o=r(1361);t.exports=function(t){return n((function(){return!!o[t]()||"​᠎"!="​᠎"[t]()||o[t].name!==t}))}},3111:(t,e,r)=>{var n=r(4488),o="["+r(1361)+"]",i=RegExp("^"+o+o+"*"),a=RegExp(o+o+"*$"),c=function(t){return function(e){var r=String(n(e));return 1&t&&(r=r.replace(i,"")),2&t&&(r=r.replace(a,"")),r}};t.exports={start:c(1),end:c(2),trim:c(3)}},863:(t,e,r)=>{var n=r(4326);t.exports=function(t){if("number"!=typeof t&&"Number"!=n(t))throw TypeError("Incorrect invocation");return+t}},1400:(t,e,r)=>{var n=r(9958),o=Math.max,i=Math.min;t.exports=function(t,e){var r=n(t);return r<0?o(r+e,0):i(r,e)}},5656:(t,e,r)=>{var n=r(8361),o=r(4488);t.exports=function(t){return n(o(t))}},9958:t=>{var e=Math.ceil,r=Math.floor;t.exports=function(t){return isNaN(t=+t)?0:(t>0?r:e)(t)}},7466:(t,e,r)=>{var n=r(9958),o=Math.min;t.exports=function(t){return t>0?o(n(t),9007199254740991):0}},7908:(t,e,r)=>{var n=r(4488);t.exports=function(t){return Object(n(t))}},7593:(t,e,r)=>{var n=r(111);t.exports=function(t,e){if(!n(t))return t;var r,o;if(e&&"function"==typeof(r=t.toString)&&!n(o=r.call(t)))return o;if("function"==typeof(r=t.valueOf)&&!n(o=r.call(t)))return o;if(!e&&"function"==typeof(r=t.toString)&&!n(o=r.call(t)))return o;throw TypeError("Can't convert object to primitive value")}},1694:(t,e,r)=>{var n={};n[r(5112)("toStringTag")]="z",t.exports="[object z]"===String(n)},9711:t=>{var e=0,r=Math.random();t.exports=function(t){return"Symbol("+String(void 0===t?"":t)+")_"+(++e+r).toString(36)}},3307:(t,e,r)=>{var n=r(133);t.exports=n&&!Symbol.sham&&"symbol"==typeof Symbol.iterator},6061:(t,e,r)=>{var n=r(5112);e.f=n},5112:(t,e,r)=>{var n=r(7854),o=r(2309),i=r(6656),a=r(9711),c=r(133),s=r(3307),u=o("wks"),l=n.Symbol,p=s?l:l&&l.withoutSetter||a;t.exports=function(t){return i(u,t)&&(c||"string"==typeof u[t])||(c&&i(l,t)?u[t]=l[t]:u[t]=p("Symbol."+t)),u[t]}},1361:t=>{t.exports="\t\n\v\f\r                　\u2028\u2029\ufeff"},2222:(t,e,r)=>{"use strict";var n=r(2109),o=r(7293),i=r(3157),a=r(111),c=r(7908),s=r(7466),u=r(6135),l=r(5417),p=r(1194),f=r(5112),v=r(7392),h=f("isConcatSpreadable"),d=9007199254740991,g="Maximum allowed index exceeded",y=v>=51||!o((function(){var t=[];return t[h]=!1,t.concat()[0]!==t})),b=p("concat"),m=function(t){if(!a(t))return!1;var e=t[h];return void 0!==e?!!e:i(t)};n({target:"Array",proto:!0,forced:!y||!b},{concat:function(t){var e,r,n,o,i,a=c(this),p=l(a,0),f=0;for(e=-1,n=arguments.length;e<n;e++)if(m(i=-1===e?a:arguments[e])){if(f+(o=s(i.length))>d)throw TypeError(g);for(r=0;r<o;r++,f++)r in i&&u(p,f,i[r])}else{if(f>=d)throw TypeError(g);u(p,f++,i)}return p.length=f,p}})},7327:(t,e,r)=>{"use strict";var n=r(2109),o=r(2092).filter;n({target:"Array",proto:!0,forced:!r(1194)("filter")},{filter:function(t){return o(this,t,arguments.length>1?arguments[1]:void 0)}})},9826:(t,e,r)=>{"use strict";var n=r(2109),o=r(2092).find,i=r(1223),a="find",c=!0;a in[]&&Array(1).find((function(){c=!1})),n({target:"Array",proto:!0,forced:c},{find:function(t){return o(this,t,arguments.length>1?arguments[1]:void 0)}}),i(a)},1038:(t,e,r)=>{var n=r(2109),o=r(8457);n({target:"Array",stat:!0,forced:!r(7072)((function(t){Array.from(t)}))},{from:o})},6699:(t,e,r)=>{"use strict";var n=r(2109),o=r(1318).includes,i=r(1223);n({target:"Array",proto:!0},{includes:function(t){return o(this,t,arguments.length>1?arguments[1]:void 0)}}),i("includes")},6992:(t,e,r)=>{"use strict";var n=r(5656),o=r(1223),i=r(7497),a=r(9909),c=r(654),s="Array Iterator",u=a.set,l=a.getterFor(s);t.exports=c(Array,"Array",(function(t,e){u(this,{type:s,target:n(t),index:0,kind:e})}),(function(){var t=l(this),e=t.target,r=t.kind,n=t.index++;return!e||n>=e.length?(t.target=void 0,{value:void 0,done:!0}):"keys"==r?{value:n,done:!1}:"values"==r?{value:e[n],done:!1}:{value:[n,e[n]],done:!1}}),"values"),i.Arguments=i.Array,o("keys"),o("values"),o("entries")},9600:(t,e,r)=>{"use strict";var n=r(2109),o=r(8361),i=r(5656),a=r(9341),c=[].join,s=o!=Object,u=a("join",",");n({target:"Array",proto:!0,forced:s||!u},{join:function(t){return c.call(i(this),void 0===t?",":t)}})},1249:(t,e,r)=>{"use strict";var n=r(2109),o=r(2092).map;n({target:"Array",proto:!0,forced:!r(1194)("map")},{map:function(t){return o(this,t,arguments.length>1?arguments[1]:void 0)}})},7042:(t,e,r)=>{"use strict";var n=r(2109),o=r(111),i=r(3157),a=r(1400),c=r(7466),s=r(5656),u=r(6135),l=r(5112),p=r(1194)("slice"),f=l("species"),v=[].slice,h=Math.max;n({target:"Array",proto:!0,forced:!p},{slice:function(t,e){var r,n,l,p=s(this),d=c(p.length),g=a(t,d),y=a(void 0===e?d:e,d);if(i(p)&&("function"!=typeof(r=p.constructor)||r!==Array&&!i(r.prototype)?o(r)&&null===(r=r[f])&&(r=void 0):r=void 0,r===Array||void 0===r))return v.call(p,g,y);for(n=new(void 0===r?Array:r)(h(y-g,0)),l=0;g<y;g++,l++)g in p&&u(n,l,p[g]);return n.length=l,n}})},561:(t,e,r)=>{"use strict";var n=r(2109),o=r(1400),i=r(9958),a=r(7466),c=r(7908),s=r(5417),u=r(6135),l=r(1194)("splice"),p=Math.max,f=Math.min,v=9007199254740991,h="Maximum allowed length exceeded";n({target:"Array",proto:!0,forced:!l},{splice:function(t,e){var r,n,l,d,g,y,b=c(this),m=a(b.length),x=o(t,m),w=arguments.length;if(0===w?r=n=0:1===w?(r=0,n=m-x):(r=w-2,n=f(p(i(e),0),m-x)),m+r-n>v)throw TypeError(h);for(l=s(b,n),d=0;d<n;d++)(g=x+d)in b&&u(l,d,b[g]);if(l.length=n,r<n){for(d=x;d<m-n;d++)y=d+r,(g=d+n)in b?b[y]=b[g]:delete b[y];for(d=m;d>m-n+r;d--)delete b[d-1]}else if(r>n)for(d=m-n;d>x;d--)y=d+r-1,(g=d+n-1)in b?b[y]=b[g]:delete b[y];for(d=0;d<r;d++)b[d+x]=arguments[d+2];return b.length=m-n+r,l}})},8309:(t,e,r)=>{var n=r(9781),o=r(3070).f,i=Function.prototype,a=i.toString,c=/^\s*function ([^ (]*)/,s="name";n&&!(s in i)&&o(i,s,{configurable:!0,get:function(){try{return a.call(this).match(c)[1]}catch(t){return""}}})},9653:(t,e,r)=>{"use strict";var n=r(9781),o=r(7854),i=r(4705),a=r(1320),c=r(6656),s=r(4326),u=r(9587),l=r(7593),p=r(7293),f=r(30),v=r(8006).f,h=r(1236).f,d=r(3070).f,g=r(3111).trim,y="Number",b=o.Number,m=b.prototype,x=s(f(m))==y,w=function(t){var e,r,n,o,i,a,c,s,u=l(t,!1);if("string"==typeof u&&u.length>2)if(43===(e=(u=g(u)).charCodeAt(0))||45===e){if(88===(r=u.charCodeAt(2))||120===r)return NaN}else if(48===e){switch(u.charCodeAt(1)){case 66:case 98:n=2,o=49;break;case 79:case 111:n=8,o=55;break;default:return+u}for(a=(i=u.slice(2)).length,c=0;c<a;c++)if((s=i.charCodeAt(c))<48||s>o)return NaN;return parseInt(i,n)}return+u};if(i(y,!b(" 0o1")||!b("0b1")||b("+0x1"))){for(var S,O=function(t){var e=arguments.length<1?0:t,r=this;return r instanceof O&&(x?p((function(){m.valueOf.call(r)})):s(r)!=y)?u(new b(w(e)),r,O):w(e)},_=n?v(b):"MAX_VALUE,MIN_VALUE,NaN,NEGATIVE_INFINITY,POSITIVE_INFINITY,EPSILON,isFinite,isInteger,isNaN,isSafeInteger,MAX_SAFE_INTEGER,MIN_SAFE_INTEGER,parseFloat,parseInt,isInteger,fromString,range".split(","),A=0;_.length>A;A++)c(b,S=_[A])&&!c(O,S)&&d(O,S,h(b,S));O.prototype=m,m.constructor=O,a(o,y,O)}},6977:(t,e,r)=>{"use strict";var n=r(2109),o=r(9958),i=r(863),a=r(8415),c=r(7293),s=1..toFixed,u=Math.floor,l=function(t,e,r){return 0===e?r:e%2==1?l(t,e-1,r*t):l(t*t,e/2,r)},p=function(t,e,r){for(var n=-1,o=r;++n<6;)o+=e*t[n],t[n]=o%1e7,o=u(o/1e7)},f=function(t,e){for(var r=6,n=0;--r>=0;)n+=t[r],t[r]=u(n/e),n=n%e*1e7},v=function(t){for(var e=6,r="";--e>=0;)if(""!==r||0===e||0!==t[e]){var n=String(t[e]);r=""===r?n:r+a.call("0",7-n.length)+n}return r};n({target:"Number",proto:!0,forced:s&&("0.000"!==8e-5.toFixed(3)||"1"!==.9.toFixed(0)||"1.25"!==1.255.toFixed(2)||"1000000000000000128"!==(0xde0b6b3a7640080).toFixed(0))||!c((function(){s.call({})}))},{toFixed:function(t){var e,r,n,c,s=i(this),u=o(t),h=[0,0,0,0,0,0],d="",g="0";if(u<0||u>20)throw RangeError("Incorrect fraction digits");if(s!=s)return"NaN";if(s<=-1e21||s>=1e21)return String(s);if(s<0&&(d="-",s=-s),s>1e-21)if(r=(e=function(t){for(var e=0,r=t;r>=4096;)e+=12,r/=4096;for(;r>=2;)e+=1,r/=2;return e}(s*l(2,69,1))-69)<0?s*l(2,-e,1):s/l(2,e,1),r*=4503599627370496,(e=52-e)>0){for(p(h,0,r),n=u;n>=7;)p(h,1e7,0),n-=7;for(p(h,l(10,n,1),0),n=e-1;n>=23;)f(h,1<<23),n-=23;f(h,1<<n),p(h,1,1),f(h,2),g=v(h)}else p(h,0,r),p(h,1<<-e,0),g=v(h)+a.call("0",u);return g=u>0?d+((c=g.length)<=u?"0."+a.call("0",u-c)+g:g.slice(0,c-u)+"."+g.slice(c-u)):d+g}})},9601:(t,e,r)=>{var n=r(2109),o=r(1574);n({target:"Object",stat:!0,forced:Object.assign!==o},{assign:o})},5003:(t,e,r)=>{var n=r(2109),o=r(7293),i=r(5656),a=r(1236).f,c=r(9781),s=o((function(){a(1)}));n({target:"Object",stat:!0,forced:!c||s,sham:!c},{getOwnPropertyDescriptor:function(t,e){return a(i(t),e)}})},9337:(t,e,r)=>{var n=r(2109),o=r(9781),i=r(3887),a=r(5656),c=r(1236),s=r(6135);n({target:"Object",stat:!0,sham:!o},{getOwnPropertyDescriptors:function(t){for(var e,r,n=a(t),o=c.f,u=i(n),l={},p=0;u.length>p;)void 0!==(r=o(n,e=u[p++]))&&s(l,e,r);return l}})},7941:(t,e,r)=>{var n=r(2109),o=r(7908),i=r(1956);n({target:"Object",stat:!0,forced:r(7293)((function(){i(1)}))},{keys:function(t){return i(o(t))}})},1539:(t,e,r)=>{var n=r(1694),o=r(1320),i=r(288);n||o(Object.prototype,"toString",i,{unsafe:!0})},4916:(t,e,r)=>{"use strict";var n=r(2109),o=r(2261);n({target:"RegExp",proto:!0,forced:/./.exec!==o},{exec:o})},9714:(t,e,r)=>{"use strict";var n=r(1320),o=r(9670),i=r(7293),a=r(7066),c="toString",s=RegExp.prototype,u=s.toString,l=i((function(){return"/a/b"!=u.call({source:"a",flags:"b"})})),p=u.name!=c;(l||p)&&n(RegExp.prototype,c,(function(){var t=o(this),e=String(t.source),r=t.flags;return"/"+e+"/"+String(void 0===r&&t instanceof RegExp&&!("flags"in s)?a.call(t):r)}),{unsafe:!0})},8783:(t,e,r)=>{"use strict";var n=r(8710).charAt,o=r(9909),i=r(654),a="String Iterator",c=o.set,s=o.getterFor(a);i(String,"String",(function(t){c(this,{type:a,string:String(t),index:0})}),(function(){var t,e=s(this),r=e.string,o=e.index;return o>=r.length?{value:void 0,done:!0}:(t=n(r,o),e.index+=t.length,{value:t,done:!1})}))},4723:(t,e,r)=>{"use strict";var n=r(7007),o=r(9670),i=r(7466),a=r(4488),c=r(1530),s=r(7651);n("match",(function(t,e,r){return[function(e){var r=a(this),n=null==e?void 0:e[t];return void 0!==n?n.call(e,r):new RegExp(e)[t](String(r))},function(t){var n=r(e,this,t);if(n.done)return n.value;var a=o(this),u=String(t);if(!a.global)return s(a,u);var l=a.unicode;a.lastIndex=0;for(var p,f=[],v=0;null!==(p=s(a,u));){var h=String(p[0]);f[v]=h,""===h&&(a.lastIndex=c(u,i(a.lastIndex),l)),v++}return 0===v?null:f}]}))},3112:(t,e,r)=>{"use strict";var n=r(2109),o=r(6650).start;n({target:"String",proto:!0,forced:r(4986)},{padStart:function(t){return o(this,t,arguments.length>1?arguments[1]:void 0)}})},2481:(t,e,r)=>{r(2109)({target:"String",proto:!0},{repeat:r(8415)})},5306:(t,e,r)=>{"use strict";var n=r(7007),o=r(7293),i=r(9670),a=r(7466),c=r(9958),s=r(4488),u=r(1530),l=r(647),p=r(7651),f=r(5112)("replace"),v=Math.max,h=Math.min,d="$0"==="a".replace(/./,"$0"),g=!!/./[f]&&""===/./[f]("a","$0");n("replace",(function(t,e,r){var n=g?"$":"$0";return[function(t,r){var n=s(this),o=null==t?void 0:t[f];return void 0!==o?o.call(t,n,r):e.call(String(n),t,r)},function(t,o){if("string"==typeof o&&-1===o.indexOf(n)&&-1===o.indexOf("$<")){var s=r(e,this,t,o);if(s.done)return s.value}var f=i(this),d=String(t),g="function"==typeof o;g||(o=String(o));var y=f.global;if(y){var b=f.unicode;f.lastIndex=0}for(var m=[];;){var x=p(f,d);if(null===x)break;if(m.push(x),!y)break;""===String(x[0])&&(f.lastIndex=u(d,a(f.lastIndex),b))}for(var w,S="",O=0,_=0;_<m.length;_++){x=m[_];for(var A=String(x[0]),j=v(h(c(x.index),d.length),0),E=[],P=1;P<x.length;P++)E.push(void 0===(w=x[P])?w:String(w));var k=x.groups;if(g){var C=[A].concat(E,j,d);void 0!==k&&C.push(k);var I=String(o.apply(void 0,C))}else I=l(A,d,j,E,k,o);j>=O&&(S+=d.slice(O,j)+I,O=j+A.length)}return S+d.slice(O)}]}),!!o((function(){var t=/./;return t.exec=function(){var t=[];return t.groups={a:"7"},t},"7"!=="".replace(t,"$<a>")}))||!d||g)},3123:(t,e,r)=>{"use strict";var n=r(7007),o=r(7850),i=r(9670),a=r(4488),c=r(6707),s=r(1530),u=r(7466),l=r(7651),p=r(2261),f=r(2999),v=r(7293),h=f.UNSUPPORTED_Y,d=[].push,g=Math.min,y=4294967295;n("split",(function(t,e,r){var n;return n="c"=="abbc".split(/(b)*/)[1]||4!="test".split(/(?:)/,-1).length||2!="ab".split(/(?:ab)*/).length||4!=".".split(/(.?)(.?)/).length||".".split(/()()/).length>1||"".split(/.?/).length?function(t,r){var n=String(a(this)),i=void 0===r?y:r>>>0;if(0===i)return[];if(void 0===t)return[n];if(!o(t))return e.call(n,t,i);for(var c,s,u,l=[],f=(t.ignoreCase?"i":"")+(t.multiline?"m":"")+(t.unicode?"u":"")+(t.sticky?"y":""),v=0,h=new RegExp(t.source,f+"g");(c=p.call(h,n))&&!((s=h.lastIndex)>v&&(l.push(n.slice(v,c.index)),c.length>1&&c.index<n.length&&d.apply(l,c.slice(1)),u=c[0].length,v=s,l.length>=i));)h.lastIndex===c.index&&h.lastIndex++;return v===n.length?!u&&h.test("")||l.push(""):l.push(n.slice(v)),l.length>i?l.slice(0,i):l}:"0".split(void 0,0).length?function(t,r){return void 0===t&&0===r?[]:e.call(this,t,r)}:e,[function(e,r){var o=a(this),i=null==e?void 0:e[t];return void 0!==i?i.call(e,o,r):n.call(String(o),e,r)},function(t,o){var a=r(n,this,t,o,n!==e);if(a.done)return a.value;var p=i(this),f=String(t),v=c(p,RegExp),d=p.unicode,b=(p.ignoreCase?"i":"")+(p.multiline?"m":"")+(p.unicode?"u":"")+(h?"g":"y"),m=new v(h?"^(?:"+p.source+")":p,b),x=void 0===o?y:o>>>0;if(0===x)return[];if(0===f.length)return null===l(m,f)?[f]:[];for(var w=0,S=0,O=[];S<f.length;){m.lastIndex=h?0:S;var _,A=l(m,h?f.slice(S):f);if(null===A||(_=g(u(m.lastIndex+(h?S:0)),f.length))===w)S=s(f,S,d);else{if(O.push(f.slice(w,S)),O.length===x)return O;for(var j=1;j<=A.length-1;j++)if(O.push(A[j]),O.length===x)return O;S=w=_}}return O.push(f.slice(w)),O}]}),!!v((function(){var t=/(?:)/,e=t.exec;t.exec=function(){return e.apply(this,arguments)};var r="ab".split(t);return 2!==r.length||"a"!==r[0]||"b"!==r[1]})),h)},6755:(t,e,r)=>{"use strict";var n,o=r(2109),i=r(1236).f,a=r(7466),c=r(3929),s=r(4488),u=r(4964),l=r(1913),p="".startsWith,f=Math.min,v=u("startsWith");o({target:"String",proto:!0,forced:!!(l||v||(n=i(String.prototype,"startsWith"),!n||n.writable))&&!v},{startsWith:function(t){var e=String(s(this));c(t);var r=a(f(arguments.length>1?arguments[1]:void 0,e.length)),n=String(t);return p?p.call(e,n,r):e.slice(r,r+n.length)===n}})},3210:(t,e,r)=>{"use strict";var n=r(2109),o=r(3111).trim;n({target:"String",proto:!0,forced:r(6091)("trim")},{trim:function(){return o(this)}})},1817:(t,e,r)=>{"use strict";var n=r(2109),o=r(9781),i=r(7854),a=r(6656),c=r(111),s=r(3070).f,u=r(9920),l=i.Symbol;if(o&&"function"==typeof l&&(!("description"in l.prototype)||void 0!==l().description)){var p={},f=function(){var t=arguments.length<1||void 0===arguments[0]?void 0:String(arguments[0]),e=this instanceof f?new l(t):void 0===t?l():l(t);return""===t&&(p[e]=!0),e};u(f,l);var v=f.prototype=l.prototype;v.constructor=f;var h=v.toString,d="Symbol(test)"==String(l("test")),g=/^Symbol\((.*)\)[^)]+$/;s(v,"description",{configurable:!0,get:function(){var t=c(this)?this.valueOf():this,e=h.call(t);if(a(p,t))return"";var r=d?e.slice(7,-1):e.replace(g,"$1");return""===r?void 0:r}}),n({global:!0,forced:!0},{Symbol:f})}},2165:(t,e,r)=>{r(7235)("iterator")},2526:(t,e,r)=>{"use strict";var n=r(2109),o=r(7854),i=r(5005),a=r(1913),c=r(9781),s=r(133),u=r(3307),l=r(7293),p=r(6656),f=r(3157),v=r(111),h=r(9670),d=r(7908),g=r(5656),y=r(7593),b=r(9114),m=r(30),x=r(1956),w=r(8006),S=r(1156),O=r(5181),_=r(1236),A=r(3070),j=r(5296),E=r(8880),P=r(1320),k=r(2309),C=r(6200),I=r(3501),T=r(9711),R=r(5112),L=r(6061),N=r(7235),M=r(8003),D=r(9909),F=r(2092).forEach,B=C("hidden"),H="Symbol",$=R("toPrimitive"),U=D.set,V=D.getterFor(H),G=Object.prototype,W=o.Symbol,z=i("JSON","stringify"),Y=_.f,X=A.f,K=S.f,q=j.f,J=k("symbols"),Q=k("op-symbols"),Z=k("string-to-symbol-registry"),tt=k("symbol-to-string-registry"),et=k("wks"),rt=o.QObject,nt=!rt||!rt.prototype||!rt.prototype.findChild,ot=c&&l((function(){return 7!=m(X({},"a",{get:function(){return X(this,"a",{value:7}).a}})).a}))?function(t,e,r){var n=Y(G,e);n&&delete G[e],X(t,e,r),n&&t!==G&&X(G,e,n)}:X,it=function(t,e){var r=J[t]=m(W.prototype);return U(r,{type:H,tag:t,description:e}),c||(r.description=e),r},at=u?function(t){return"symbol"==typeof t}:function(t){return Object(t)instanceof W},ct=function(t,e,r){t===G&&ct(Q,e,r),h(t);var n=y(e,!0);return h(r),p(J,n)?(r.enumerable?(p(t,B)&&t[B][n]&&(t[B][n]=!1),r=m(r,{enumerable:b(0,!1)})):(p(t,B)||X(t,B,b(1,{})),t[B][n]=!0),ot(t,n,r)):X(t,n,r)},st=function(t,e){h(t);var r=g(e),n=x(r).concat(ft(r));return F(n,(function(e){c&&!ut.call(r,e)||ct(t,e,r[e])})),t},ut=function(t){var e=y(t,!0),r=q.call(this,e);return!(this===G&&p(J,e)&&!p(Q,e))&&(!(r||!p(this,e)||!p(J,e)||p(this,B)&&this[B][e])||r)},lt=function(t,e){var r=g(t),n=y(e,!0);if(r!==G||!p(J,n)||p(Q,n)){var o=Y(r,n);return!o||!p(J,n)||p(r,B)&&r[B][n]||(o.enumerable=!0),o}},pt=function(t){var e=K(g(t)),r=[];return F(e,(function(t){p(J,t)||p(I,t)||r.push(t)})),r},ft=function(t){var e=t===G,r=K(e?Q:g(t)),n=[];return F(r,(function(t){!p(J,t)||e&&!p(G,t)||n.push(J[t])})),n};(s||(P((W=function(){if(this instanceof W)throw TypeError("Symbol is not a constructor");var t=arguments.length&&void 0!==arguments[0]?String(arguments[0]):void 0,e=T(t),r=function(t){this===G&&r.call(Q,t),p(this,B)&&p(this[B],e)&&(this[B][e]=!1),ot(this,e,b(1,t))};return c&&nt&&ot(G,e,{configurable:!0,set:r}),it(e,t)}).prototype,"toString",(function(){return V(this).tag})),P(W,"withoutSetter",(function(t){return it(T(t),t)})),j.f=ut,A.f=ct,_.f=lt,w.f=S.f=pt,O.f=ft,L.f=function(t){return it(R(t),t)},c&&(X(W.prototype,"description",{configurable:!0,get:function(){return V(this).description}}),a||P(G,"propertyIsEnumerable",ut,{unsafe:!0}))),n({global:!0,wrap:!0,forced:!s,sham:!s},{Symbol:W}),F(x(et),(function(t){N(t)})),n({target:H,stat:!0,forced:!s},{for:function(t){var e=String(t);if(p(Z,e))return Z[e];var r=W(e);return Z[e]=r,tt[r]=e,r},keyFor:function(t){if(!at(t))throw TypeError(t+" is not a symbol");if(p(tt,t))return tt[t]},useSetter:function(){nt=!0},useSimple:function(){nt=!1}}),n({target:"Object",stat:!0,forced:!s,sham:!c},{create:function(t,e){return void 0===e?m(t):st(m(t),e)},defineProperty:ct,defineProperties:st,getOwnPropertyDescriptor:lt}),n({target:"Object",stat:!0,forced:!s},{getOwnPropertyNames:pt,getOwnPropertySymbols:ft}),n({target:"Object",stat:!0,forced:l((function(){O.f(1)}))},{getOwnPropertySymbols:function(t){return O.f(d(t))}}),z)&&n({target:"JSON",stat:!0,forced:!s||l((function(){var t=W();return"[null]"!=z([t])||"{}"!=z({a:t})||"{}"!=z(Object(t))}))},{stringify:function(t,e,r){for(var n,o=[t],i=1;arguments.length>i;)o.push(arguments[i++]);if(n=e,(v(e)||void 0!==t)&&!at(t))return f(e)||(e=function(t,e){if("function"==typeof n&&(e=n.call(this,t,e)),!at(e))return e}),o[1]=e,z.apply(null,o)}});W.prototype[$]||E(W.prototype,$,W.prototype.valueOf),M(W,H),I[B]=!0},4747:(t,e,r)=>{var n=r(7854),o=r(8324),i=r(8533),a=r(8880);for(var c in o){var s=n[c],u=s&&s.prototype;if(u&&u.forEach!==i)try{a(u,"forEach",i)}catch(t){u.forEach=i}}},3948:(t,e,r)=>{var n=r(7854),o=r(8324),i=r(6992),a=r(8880),c=r(5112),s=c("iterator"),u=c("toStringTag"),l=i.values;for(var p in o){var f=n[p],v=f&&f.prototype;if(v){if(v[s]!==l)try{a(v,s,l)}catch(t){v[s]=l}if(v[u]||a(v,u,p),o[p])for(var h in i)if(v[h]!==i[h])try{a(v,h,i[h])}catch(t){v[h]=i[h]}}}}},e={};function r(n){var o=e[n];if(void 0!==o)return o.exports;var i=e[n]={exports:{}};return t[n](i,i.exports,r),i.exports}r.d=(t,e)=>{for(var n in e)r.o(e,n)&&!r.o(t,n)&&Object.defineProperty(t,n,{enumerable:!0,get:e[n]})},r.g=function(){if("object"==typeof globalThis)return globalThis;try{return this||new Function("return this")()}catch(t){if("object"==typeof window)return window}}(),r.o=(t,e)=>Object.prototype.hasOwnProperty.call(t,e),r.r=t=>{"undefined"!=typeof Symbol&&Symbol.toStringTag&&Object.defineProperty(t,Symbol.toStringTag,{value:"Module"}),Object.defineProperty(t,"__esModule",{value:!0})};var n={};return(()=>{"use strict";r.d(n,{default:()=>G});var t={};r.r(t),r.d(t,{adjustableInputNumbers:()=>d,createElementFromString:()=>p,createFromTemplate:()=>f,eventPath:()=>v,off:()=>l,on:()=>u,resolveElement:()=>h});r(9601),r(6699),r(4747),r(2481),r(4916),r(4723),r(1539),r(9714),r(2222),r(9653),r(6992),r(3948),r(561),r(7941),r(9826),r(6755),r(2526),r(7327),r(5003),r(9337),r(7042),r(8309),r(1038),r(8783),r(1817),r(2165),r(3210),r(3123),r(5306);function e(t,e){var r=Object.keys(t);if(Object.getOwnPropertySymbols){var n=Object.getOwnPropertySymbols(t);e&&(n=n.filter((function(e){return Object.getOwnPropertyDescriptor(t,e).enumerable}))),r.push.apply(r,n)}return r}function o(t){for(var r=1;r<arguments.length;r++){var n=null!=arguments[r]?arguments[r]:{};r%2?e(Object(n),!0).forEach((function(e){i(t,e,n[e])})):Object.getOwnPropertyDescriptors?Object.defineProperties(t,Object.getOwnPropertyDescriptors(n)):e(Object(n)).forEach((function(e){Object.defineProperty(t,e,Object.getOwnPropertyDescriptor(n,e))}))}return t}function i(t,e,r){return e in t?Object.defineProperty(t,e,{value:r,enumerable:!0,configurable:!0,writable:!0}):t[e]=r,t}function a(t,e){var r="undefined"!=typeof Symbol&&t[Symbol.iterator]||t["@@iterator"];if(r)return(r=r.call(t)).next.bind(r);if(Array.isArray(t)||(r=function(t,e){if(!t)return;if("string"==typeof t)return c(t,e);var r=Object.prototype.toString.call(t).slice(8,-1);"Object"===r&&t.constructor&&(r=t.constructor.name);if("Map"===r||"Set"===r)return Array.from(t);if("Arguments"===r||/^(?:Ui|I)nt(?:8|16|32)(?:Clamped)?Array$/.test(r))return c(t,e)}(t))||e&&t&&"number"==typeof t.length){r&&(t=r);var n=0;return function(){return n>=t.length?{done:!0}:{done:!1,value:t[n++]}}}throw new TypeError("Invalid attempt to iterate non-iterable instance.\nIn order to be iterable, non-array objects must have a [Symbol.iterator]() method.")}function c(t,e){(null==e||e>t.length)&&(e=t.length);for(var r=0,n=new Array(e);r<e;r++)n[r]=t[r];return n}function s(t,e,r,n){var i=arguments.length>4&&void 0!==arguments[4]?arguments[4]:{};e instanceof HTMLCollection||e instanceof NodeList?e=Array.from(e):Array.isArray(e)||(e=[e]),Array.isArray(r)||(r=[r]);for(var c,s=a(e);!(c=s()).done;)for(var u,l=c.value,p=a(r);!(u=p()).done;){var f=u.value;l[t](f,n,o({capture:!1},i))}return Array.prototype.slice.call(arguments,1)}var u=s.bind(null,"addEventListener"),l=s.bind(null,"removeEventListener");function p(t){var e=document.createElement("div");return e.innerHTML=t.trim(),e.firstElementChild}function f(t){var e=function(t,e){var r=t.getAttribute(e);return t.removeAttribute(e),r};return function t(r){var n=arguments.length>1&&void 0!==arguments[1]?arguments[1]:{},o=e(r,":obj"),i=e(r,":ref"),a=o?n[o]={}:n;i&&(n[i]=r);for(var c=0,s=Array.from(r.children);c<s.length;c++){var u=s[c],l=e(u,":arr"),p=t(u,l?{}:a);l&&(a[l]||(a[l]=[])).push(Object.keys(p).length?p:u)}return n}(p(t))}function v(t){var e=t.path||t.composedPath&&t.composedPath();if(e)return e;var r=t.target.parentElement;for(e=[t.target,r];r=r.parentElement;)e.push(r);return e.push(document,window),e}function h(t){return t instanceof Element?t:"string"==typeof t?t.split(/>>/g).reduce((function(t,e,r,n){return t=t.querySelector(e),r<n.length-1?t.shadowRoot:t}),document):null}function d(t){var e=arguments.length>1&&void 0!==arguments[1]?arguments[1]:function(t){return t};function r(r){var n=[.001,.01,.1][Number(r.shiftKey||2*r.ctrlKey)]*(r.deltaY<0?1:-1),o=0,i=t.selectionStart;t.value=t.value.replace(/[\d.]+/g,(function(t,r){return r<=i&&r+t.length>=i?(i=r,e(Number(t),n,o)):(o++,t)})),t.focus(),t.setSelectionRange(i,i),r.preventDefault(),t.dispatchEvent(new Event("input"))}u(t,"focus",(function(){return u(window,"wheel",r,{passive:!1})})),u(t,"blur",(function(){return l(window,"wheel",r)}))}r(1249),r(3112),r(9600);var g=Math.min,y=Math.max,b=Math.floor,m=Math.round;function x(t,e,r){e/=100,r/=100;var n=b(t=t/360*6),o=t-n,i=r*(1-e),a=r*(1-o*e),c=r*(1-(1-o)*e),s=n%6;return[255*[r,a,i,i,c,r][s],255*[c,r,r,a,i,i][s],255*[i,i,c,r,r,a][s]]}function w(t,e,r){return x(t,e,r).map((function(t){return m(t).toString(16).padStart(2,"0")}))}function S(t,e,r){var n=x(t,e,r),o=n[0]/255,i=n[1]/255,a=n[2]/255,c=g(1-o,1-i,1-a);return[100*(1===c?0:(1-o-c)/(1-c)),100*(1===c?0:(1-i-c)/(1-c)),100*(1===c?0:(1-a-c)/(1-c)),100*c]}function O(t,e,r){var n=(2-(e/=100))*(r/=100)/2;return 0!==n&&(e=1===n?0:n<.5?e*r/(2*n):e*r/(2-2*n)),[t,100*e,100*n]}function _(t,e,r){var n,o,i=g(t/=255,e/=255,r/=255),a=y(t,e,r),c=a-i;if(0===c)n=o=0;else{o=c/a;var s=((a-t)/6+c/2)/c,u=((a-e)/6+c/2)/c,l=((a-r)/6+c/2)/c;t===a?n=l-u:e===a?n=1/3+s-l:r===a&&(n=2/3+u-s),n<0?n+=1:n>1&&(n-=1)}return[360*n,100*o,100*a]}function A(t,e,r,n){e/=100,r/=100;var o=255*(1-g(1,(t/=100)*(1-(n/=100))+n)),i=255*(1-g(1,e*(1-n)+n)),a=255*(1-g(1,r*(1-n)+n));return[].concat(_(o,i,a))}function j(t,e,r){e/=100;var n=2*(e*=(r/=100)<.5?r:1-r)/(r+e)*100,o=100*(r+e);return[t,isNaN(n)?0:n,o]}function E(t){return _.apply(void 0,t.match(/.{2}/g).map((function(t){return parseInt(t,16)})))}function P(t){t=t.match(/^[a-zA-Z]+$/)?function(t){if("black"===t.toLowerCase())return"#000";var e=document.createElement("canvas").getContext("2d");return e.fillStyle=t,"#000"===e.fillStyle?null:e.fillStyle}(t):t;var e,r={cmyk:/^cmyk[\D]+([\d.]+)[\D]+([\d.]+)[\D]+([\d.]+)[\D]+([\d.]+)/i,rgba:/^((rgba)|rgb)[\D]+([\d.]+)[\D]+([\d.]+)[\D]+([\d.]+)[\D]*?([\d.]+|$)/i,hsla:/^((hsla)|hsl)[\D]+([\d.]+)[\D]+([\d.]+)[\D]+([\d.]+)[\D]*?([\d.]+|$)/i,hsva:/^((hsva)|hsv)[\D]+([\d.]+)[\D]+([\d.]+)[\D]+([\d.]+)[\D]*?([\d.]+|$)/i,hexa:/^#?(([\dA-Fa-f]{3,4})|([\dA-Fa-f]{6})|([\dA-Fa-f]{8}))$/i},n=function(t){return t.map((function(t){return/^(|\d+)\.\d+|\d+$/.test(t)?Number(t):void 0}))};t:for(var o in r)if(e=r[o].exec(t)){var i=function(t){return!!e[2]==("number"==typeof t)};switch(o){case"cmyk":var a=n(e),c=a[1],s=a[2],u=a[3],l=a[4];if(c>100||s>100||u>100||l>100)break t;return{values:A(c,s,u,l),type:o};case"rgba":var p=n(e),f=p[3],v=p[4],h=p[5],d=p[6];if(f>255||v>255||h>255||d<0||d>1||!i(d))break t;return{values:[].concat(_(f,v,h),[d]),a:d,type:o};case"hexa":var g=e[1];4!==g.length&&3!==g.length||(g=g.split("").map((function(t){return t+t})).join(""));var y=g.substring(0,6),b=g.substring(6);return b=b?parseInt(b,16)/255:void 0,{values:[].concat(E(y),[b]),a:b,type:o};case"hsla":var m=n(e),x=m[3],w=m[4],S=m[5],O=m[6];if(x>360||w>100||S>100||O<0||O>1||!i(O))break t;return{values:[].concat(j(x,w,S),[O]),a:O,type:o};case"hsva":var P=n(e),k=P[3],C=P[4],I=P[5],T=P[6];if(k>360||C>100||I>100||T<0||T>1||!i(T))break t;return{values:[k,C,I,T],a:T,type:o}}}return{values:null,type:null}}r(6977);function k(){var t=arguments.length>0&&void 0!==arguments[0]?arguments[0]:0,e=arguments.length>1&&void 0!==arguments[1]?arguments[1]:0,r=arguments.length>2&&void 0!==arguments[2]?arguments[2]:0,n=arguments.length>3&&void 0!==arguments[3]?arguments[3]:1,o=function(t,e){return function(){var r=arguments.length>0&&void 0!==arguments[0]?arguments[0]:-1;return e(~r?t.map((function(t){return Number(t.toFixed(r))})):t)}},i={h:t,s:e,v:r,a:n,toHSVA:function(){var t=[i.h,i.s,i.v,i.a];return t.toString=o(t,(function(t){return"hsva("+t[0]+", "+t[1]+"%, "+t[2]+"%, "+i.a+")"})),t},toHSLA:function(){var t=[].concat(O(i.h,i.s,i.v),[i.a]);return t.toString=o(t,(function(t){return"hsla("+t[0]+", "+t[1]+"%, "+t[2]+"%, "+i.a+")"})),t},toRGBA:function(){var t=[].concat(x(i.h,i.s,i.v),[i.a]);return t.toString=o(t,(function(t){return"rgba("+t[0]+", "+t[1]+", "+t[2]+", "+i.a+")"})),t},toCMYK:function(){var t=S(i.h,i.s,i.v);return t.toString=o(t,(function(t){return"cmyk("+t[0]+"%, "+t[1]+"%, "+t[2]+"%, "+t[3]+"%)"})),t},toHEXA:function(){var t=w(i.h,i.s,i.v),e=i.a>=1?"":Number((255*i.a).toFixed(0)).toString(16).toUpperCase().padStart(2,"0");return e&&t.push(e),t.toString=function(){return"#"+t.join("").toUpperCase()},t},clone:function(){return k(i.h,i.s,i.v,i.a)}};return i}var C=function(t){return Math.max(Math.min(t,1),0)};function I(t){var e={options:Object.assign({lock:null,onchange:function(){return 0},onstop:function(){return 0}},t),_keyboard:function(t){var r=e.options,n=t.type,o=t.key;if(document.activeElement===r.wrapper){var i=e.options.lock,a="ArrowUp"===o,c="ArrowRight"===o,s="ArrowDown"===o,u="ArrowLeft"===o;if("keydown"===n&&(a||c||s||u)){var l=0,p=0;"v"===i?l=a||c?1:-1:"h"===i?l=a||c?-1:1:(p=a?-1:s?1:0,l=u?-1:c?1:0),e.update(C(e.cache.x+.01*l),C(e.cache.y+.01*p)),t.preventDefault()}else o.startsWith("Arrow")&&(e.options.onstop(),t.preventDefault())}},_tapstart:function(t){u(document,["mouseup","touchend","touchcancel"],e._tapstop),u(document,["mousemove","touchmove"],e._tapmove),t.cancelable&&t.preventDefault(),e._tapmove(t)},_tapmove:function(t){var r=e.options,n=e.cache,o=r.lock,i=r.element,a=r.wrapper.getBoundingClientRect(),c=0,s=0;if(t){var u=t&&t.touches&&t.touches[0];c=t?(u||t).clientX:0,s=t?(u||t).clientY:0,c<a.left?c=a.left:c>a.left+a.width&&(c=a.left+a.width),s<a.top?s=a.top:s>a.top+a.height&&(s=a.top+a.height),c-=a.left,s-=a.top}else n&&(c=n.x*a.width,s=n.y*a.height);"h"!==o&&(i.style.left="calc("+c/a.width*100+"% - "+i.offsetWidth/2+"px)"),"v"!==o&&(i.style.top="calc("+s/a.height*100+"% - "+i.offsetHeight/2+"px)"),e.cache={x:c/a.width,y:s/a.height};var l=C(c/a.width),p=C(s/a.height);switch(o){case"v":return r.onchange(l);case"h":return r.onchange(p);default:return r.onchange(l,p)}},_tapstop:function(){e.options.onstop(),l(document,["mouseup","touchend","touchcancel"],e._tapstop),l(document,["mousemove","touchmove"],e._tapmove)},trigger:function(){e._tapmove()},update:function(){var t=arguments.length>0&&void 0!==arguments[0]?arguments[0]:0,r=arguments.length>1&&void 0!==arguments[1]?arguments[1]:0,n=e.options.wrapper.getBoundingClientRect(),o=n.left,i=n.top,a=n.width,c=n.height;"h"===e.options.lock&&(r=t),e._tapmove({clientX:o+a*t,clientY:i+c*r})},destroy:function(){var t=e.options,r=e._tapstart,n=e._keyboard;l(document,["keydown","keyup"],n),l([t.wrapper,t.element],"mousedown",r),l([t.wrapper,t.element],"touchstart",r,{passive:!1})}},r=e.options,n=e._tapstart,o=e._keyboard;return u([r.wrapper,r.element],"mousedown",n),u([r.wrapper,r.element],"touchstart",n,{passive:!1}),u(document,["keydown","keyup"],o),e}function T(){var e=arguments.length>0&&void 0!==arguments[0]?arguments[0]:{};e=Object.assign({onchange:function(){return 0},className:"",elements:[]},e);var r=u(e.elements,"click",(function(t){e.elements.forEach((function(r){return r.classList[t.target===r?"add":"remove"](e.className)})),e.onchange(t),t.stopPropagation()}));return{destroy:function(){return l.apply(t,r)}}}function R(t,e){var r="undefined"!=typeof Symbol&&t[Symbol.iterator]||t["@@iterator"];if(r)return(r=r.call(t)).next.bind(r);if(Array.isArray(t)||(r=function(t,e){if(!t)return;if("string"==typeof t)return L(t,e);var r=Object.prototype.toString.call(t).slice(8,-1);"Object"===r&&t.constructor&&(r=t.constructor.name);if("Map"===r||"Set"===r)return Array.from(t);if("Arguments"===r||/^(?:Ui|I)nt(?:8|16|32)(?:Clamped)?Array$/.test(r))return L(t,e)}(t))||e&&t&&"number"==typeof t.length){r&&(t=r);var n=0;return function(){return n>=t.length?{done:!0}:{done:!1,value:t[n++]}}}throw new TypeError("Invalid attempt to iterate non-iterable instance.\nIn order to be iterable, non-array objects must have a [Symbol.iterator]() method.")}function L(t,e){(null==e||e>t.length)&&(e=t.length);for(var r=0,n=new Array(e);r<e;r++)n[r]=t[r];return n}function N(t,e){var r=Object.keys(t);if(Object.getOwnPropertySymbols){var n=Object.getOwnPropertySymbols(t);e&&(n=n.filter((function(e){return Object.getOwnPropertyDescriptor(t,e).enumerable}))),r.push.apply(r,n)}return r}function M(t){for(var e=1;e<arguments.length;e++){var r=null!=arguments[e]?arguments[e]:{};e%2?N(Object(r),!0).forEach((function(e){D(t,e,r[e])})):Object.getOwnPropertyDescriptors?Object.defineProperties(t,Object.getOwnPropertyDescriptors(r)):N(Object(r)).forEach((function(e){Object.defineProperty(t,e,Object.getOwnPropertyDescriptor(r,e))}))}return t}function D(t,e,r){return e in t?Object.defineProperty(t,e,{value:r,enumerable:!0,configurable:!0,writable:!0}):t[e]=r,t}
/*! NanoPop 2.1.0 MIT | https://github.com/Simonwep/nanopop */var F={variantFlipOrder:{start:"sme",middle:"mse",end:"ems"},positionFlipOrder:{top:"tbrl",right:"rltb",bottom:"btrl",left:"lrbt"},position:"bottom",margin:8},B=function(t,e,r){var n=M(M({container:document.documentElement.getBoundingClientRect()},F),r),o=n.container,i=n.margin,a=n.position,c=n.variantFlipOrder,s=n.positionFlipOrder,u=e.style,l=u.left,p=u.top;e.style.left="0",e.style.top="0";for(var f,v=t.getBoundingClientRect(),h=e.getBoundingClientRect(),d={t:v.top-h.height-i,b:v.bottom+i,r:v.right+i,l:v.left-h.width-i},g={vs:v.left,vm:v.left+v.width/2+-h.width/2,ve:v.left+v.width-h.width,hs:v.top,hm:v.bottom-v.height/2-h.height/2,he:v.bottom-h.height},y=a.split("-"),b=y[0],m=y[1],x=void 0===m?"middle":m,w=s[b],S=c[x],O=o.top,_=o.left,A=o.bottom,j=o.right,E=R(w);!(f=E()).done;){var P=f.value,k="t"===P||"b"===P,C=d[P],I=k?["top","left"]:["left","top"],T=I[0],L=I[1],N=k?[h.height,h.width]:[h.width,h.height],D=N[1],B=k?[A,j]:[j,A],H=B[1],$=k?[O,_]:[_,O],U=$[1];if(!(C<$[0]||C+N[0]>B[0]))for(var V,G=R(S);!(V=G()).done;){var W=V.value,z=g[(k?"v":"h")+W];if(!(z<U||z+D>H))return e.style[L]=z-h[L]+"px",e.style[T]=C-h[T]+"px",P+W}}return e.style.left=l,e.style.top=p,null};function H(t,e){var r="undefined"!=typeof Symbol&&t[Symbol.iterator]||t["@@iterator"];if(r)return(r=r.call(t)).next.bind(r);if(Array.isArray(t)||(r=function(t,e){if(!t)return;if("string"==typeof t)return $(t,e);var r=Object.prototype.toString.call(t).slice(8,-1);"Object"===r&&t.constructor&&(r=t.constructor.name);if("Map"===r||"Set"===r)return Array.from(t);if("Arguments"===r||/^(?:Ui|I)nt(?:8|16|32)(?:Clamped)?Array$/.test(r))return $(t,e)}(t))||e&&t&&"number"==typeof t.length){r&&(t=r);var n=0;return function(){return n>=t.length?{done:!0}:{done:!1,value:t[n++]}}}throw new TypeError("Invalid attempt to iterate non-iterable instance.\nIn order to be iterable, non-array objects must have a [Symbol.iterator]() method.")}function $(t,e){(null==e||e>t.length)&&(e=t.length);for(var r=0,n=new Array(e);r<e;r++)n[r]=t[r];return n}function U(t,e){var r=Object.keys(t);if(Object.getOwnPropertySymbols){var n=Object.getOwnPropertySymbols(t);e&&(n=n.filter((function(e){return Object.getOwnPropertyDescriptor(t,e).enumerable}))),r.push.apply(r,n)}return r}function V(t,e,r){return e in t?Object.defineProperty(t,e,{value:r,enumerable:!0,configurable:!0,writable:!0}):t[e]=r,t}var G=function(){function e(t){var r=this;V(this,"_initializingActive",!0),V(this,"_recalc",!0),V(this,"_nanopop",null),V(this,"_root",null),V(this,"_color",k()),V(this,"_lastColor",k()),V(this,"_swatchColors",[]),V(this,"_setupAnimationFrame",null),V(this,"_eventListener",{init:[],save:[],hide:[],show:[],clear:[],change:[],changestop:[],cancel:[],swatchselect:[]}),this.options=t=Object.assign(function(t){for(var e=1;e<arguments.length;e++){var r=null!=arguments[e]?arguments[e]:{};e%2?U(Object(r),!0).forEach((function(e){V(t,e,r[e])})):Object.getOwnPropertyDescriptors?Object.defineProperties(t,Object.getOwnPropertyDescriptors(r)):U(Object(r)).forEach((function(e){Object.defineProperty(t,e,Object.getOwnPropertyDescriptor(r,e))}))}return t}({},e.DEFAULT_OPTIONS),t);var n=t,o=n.swatches,i=n.components,a=n.theme,c=n.sliders,s=n.lockOpacity,u=n.padding;["nano","monolith"].includes(a)&&!c&&(t.sliders="h"),i.interaction||(i.interaction={});var l=i.preview,p=i.opacity,f=i.hue,v=i.palette;i.opacity=!s&&p,i.palette=v||l||p||f,this._preBuild(),this._buildComponents(),this._bindEvents(),this._finalBuild(),o&&o.length&&o.forEach((function(t){return r.addSwatch(t)}));var h=this._root,d=h.button,g=h.app;this._nanopop=function(t,e,r){var n="object"!=typeof t||t instanceof HTMLElement?M({reference:t,popper:e},r):t;return{update:function(){var t=arguments.length>0&&void 0!==arguments[0]?arguments[0]:n,e=Object.assign(n,t),r=e.reference,o=e.popper;if(!o||!r)throw new Error("Popper- or reference-element missing.");return B(r,o,n)}}}(d,g,{margin:u}),d.setAttribute("role","button"),d.setAttribute("aria-label",this._t("btn:toggle"));var y=this;this._setupAnimationFrame=requestAnimationFrame((function e(){if(!g.offsetWidth)return requestAnimationFrame(e);y.setColor(t.default),y._rePositioningPicker(),t.defaultRepresentation&&(y._representation=t.defaultRepresentation,y.setColorRepresentation(y._representation)),t.showAlways&&y.show(),y._initializingActive=!1,y._emit("init")}))}var r=e.prototype;return r._preBuild=function(){for(var t=this.options,e=0,r=["el","container"];e<r.length;e++){var n=r[e];t[n]=h(t[n])}this._root=function(t){var e=t.options,r=e.components,n=e.useAsButton,o=e.inline,i=e.appClass,a=e.theme,c=e.lockOpacity,s=function(t){return t?"":'style="display:none" hidden'},u=function(e){return t._t(e)},l=f('\n      <div :ref="root" class="pickr">\n\n        '+(n?"":'<button type="button" :ref="button" class="pcr-button"></button>')+'\n\n        <div :ref="app" class="pcr-app '+(i||"")+'" data-theme="'+a+'" '+(o?'style="position: unset"':"")+' aria-label="'+u("ui:dialog")+'" role="window">\n          <div class="pcr-selection" '+s(r.palette)+'>\n            <div :obj="preview" class="pcr-color-preview" '+s(r.preview)+'>\n              <button type="button" :ref="lastColor" class="pcr-last-color" aria-label="'+u("btn:last-color")+'"></button>\n              <div :ref="currentColor" class="pcr-current-color"></div>\n            </div>\n\n            <div :obj="palette" class="pcr-color-palette">\n              <div :ref="picker" class="pcr-picker"></div>\n              <div :ref="palette" class="pcr-palette" tabindex="0" aria-label="'+u("aria:palette")+'" role="listbox"></div>\n            </div>\n\n            <div :obj="hue" class="pcr-color-chooser" '+s(r.hue)+'>\n              <div :ref="picker" class="pcr-picker"></div>\n              <div :ref="slider" class="pcr-hue pcr-slider" tabindex="0" aria-label="'+u("aria:hue")+'" role="slider"></div>\n            </div>\n\n            <div :obj="opacity" class="pcr-color-opacity" '+s(r.opacity)+'>\n              <div :ref="picker" class="pcr-picker"></div>\n              <div :ref="slider" class="pcr-opacity pcr-slider" tabindex="0" aria-label="'+u("aria:opacity")+'" role="slider"></div>\n            </div>\n          </div>\n\n          <div class="pcr-swatches '+(r.palette?"":"pcr-last")+'" :ref="swatches"></div>\n\n          <div :obj="interaction" class="pcr-interaction" '+s(Object.keys(r.interaction).length)+'>\n            <input :ref="result" class="pcr-result" type="text" spellcheck="false" '+s(r.interaction.input)+' aria-label="'+u("aria:input")+'">\n\n            <input :arr="options" class="pcr-type" data-type="HEXA" value="'+(c?"HEX":"HEXA")+'" type="button" '+s(r.interaction.hex)+'>\n            <input :arr="options" class="pcr-type" data-type="RGBA" value="'+(c?"RGB":"RGBA")+'" type="button" '+s(r.interaction.rgba)+'>\n            <input :arr="options" class="pcr-type" data-type="HSLA" value="'+(c?"HSL":"HSLA")+'" type="button" '+s(r.interaction.hsla)+'>\n            <input :arr="options" class="pcr-type" data-type="HSVA" value="'+(c?"HSV":"HSVA")+'" type="button" '+s(r.interaction.hsva)+'>\n            <input :arr="options" class="pcr-type" data-type="CMYK" value="CMYK" type="button" '+s(r.interaction.cmyk)+'>\n\n            <input :ref="save" class="pcr-save" value="'+u("btn:save")+'" type="button" '+s(r.interaction.save)+' aria-label="'+u("aria:btn:save")+'">\n            <input :ref="cancel" class="pcr-cancel" value="'+u("btn:cancel")+'" type="button" '+s(r.interaction.cancel)+' aria-label="'+u("aria:btn:cancel")+'">\n            <input :ref="clear" class="pcr-clear" value="'+u("btn:clear")+'" type="button" '+s(r.interaction.clear)+' aria-label="'+u("aria:btn:clear")+'">\n          </div>\n        </div>\n      </div>\n    '),p=l.interaction;return p.options.find((function(t){return!t.hidden&&!t.classList.add("active")})),p.type=function(){return p.options.find((function(t){return t.classList.contains("active")}))},l}(this),t.useAsButton&&(this._root.button=t.el),t.container.appendChild(this._root.root)},r._finalBuild=function(){var t=this.options,e=this._root;if(t.container.removeChild(e.root),t.inline){var r=t.el.parentElement;t.el.nextSibling?r.insertBefore(e.app,t.el.nextSibling):r.appendChild(e.app)}else t.container.appendChild(e.app);t.useAsButton?t.inline&&t.el.remove():t.el.parentNode.replaceChild(e.root,t.el),t.disabled&&this.disable(),t.comparison||(e.button.style.transition="none",t.useAsButton||(e.preview.lastColor.style.transition="none")),this.hide()},r._buildComponents=function(){var t=this,e=this,r=this.options.components,n=(e.options.sliders||"v").repeat(2),o=n.match(/^[vh]+$/g)?n:[],i=o[0],a=o[1],c=function(){return t._color||(t._color=t._lastColor.clone())},s={palette:I({element:e._root.palette.picker,wrapper:e._root.palette.palette,onstop:function(){return e._emit("changestop","slider",e)},onchange:function(t,n){if(r.palette){var o=c(),i=e._root,a=e.options,s=i.preview,u=s.lastColor,l=s.currentColor;e._recalc&&(o.s=100*t,o.v=100-100*n,o.v<0&&(o.v=0),e._updateOutput("slider"));var p=o.toRGBA().toString(0);this.element.style.background=p,this.wrapper.style.background="\n                        linear-gradient(to top, rgba(0, 0, 0, "+o.a+"), transparent),\n                        linear-gradient(to left, hsla("+o.h+", 100%, 50%, "+o.a+"), rgba(255, 255, 255, "+o.a+"))\n                    ",a.comparison?a.useAsButton||e._lastColor||u.style.setProperty("--pcr-color",p):(i.button.style.setProperty("--pcr-color",p),i.button.classList.remove("clear"));for(var f,v=o.toHEXA().toString(),h=H(e._swatchColors);!(f=h()).done;){var d=f.value,g=d.el,y=d.color;g.classList[v===y.toHEXA().toString()?"add":"remove"]("pcr-active")}l.style.setProperty("--pcr-color",p)}}}),hue:I({lock:"v"===a?"h":"v",element:e._root.hue.picker,wrapper:e._root.hue.slider,onstop:function(){return e._emit("changestop","slider",e)},onchange:function(t){if(r.hue&&r.palette){var n=c();e._recalc&&(n.h=360*t),this.element.style.backgroundColor="hsl("+n.h+", 100%, 50%)",s.palette.trigger()}}}),opacity:I({lock:"v"===i?"h":"v",element:e._root.opacity.picker,wrapper:e._root.opacity.slider,onstop:function(){return e._emit("changestop","slider",e)},onchange:function(t){if(r.opacity&&r.palette){var n=c();e._recalc&&(n.a=Math.round(100*t)/100),this.element.style.background="rgba(0, 0, 0, "+n.a+")",s.palette.trigger()}}}),selectable:T({elements:e._root.interaction.options,className:"active",onchange:function(t){e._representation=t.target.getAttribute("data-type").toUpperCase(),e._recalc&&e._updateOutput("swatch")}})};this._components=s},r._bindEvents=function(){var t=this,e=this._root,r=this.options,n=[u(e.interaction.clear,"click",(function(){return t._clearColor()})),u([e.interaction.cancel,e.preview.lastColor],"click",(function(){t.setHSVA.apply(t,(t._lastColor||t._color).toHSVA().concat([!0])),t._emit("cancel")})),u(e.interaction.save,"click",(function(){!t.applyColor()&&!r.showAlways&&t.hide()})),u(e.interaction.result,["keyup","input"],(function(e){t.setColor(e.target.value,!0)&&!t._initializingActive&&(t._emit("change",t._color,"input",t),t._emit("changestop","input",t)),e.stopImmediatePropagation()})),u(e.interaction.result,["focus","blur"],(function(e){t._recalc="blur"===e.type,t._recalc&&t._updateOutput(null)})),u([e.palette.palette,e.palette.picker,e.hue.slider,e.hue.picker,e.opacity.slider,e.opacity.picker],["mousedown","touchstart"],(function(){return t._recalc=!0}),{passive:!0})];if(!r.showAlways){var o=r.closeWithKey;n.push(u(e.button,"click",(function(){return t.isOpen()?t.hide():t.show()})),u(document,"keyup",(function(e){return t.isOpen()&&(e.key===o||e.code===o)&&t.hide()})),u(document,["touchstart","mousedown"],(function(r){t.isOpen()&&!v(r).some((function(t){return t===e.app||t===e.button}))&&t.hide()}),{capture:!0}))}if(r.adjustableNumbers){var i={rgba:[255,255,255,1],hsva:[360,100,100,1],hsla:[360,100,100,1],cmyk:[100,100,100,100]};d(e.interaction.result,(function(e,r,n){var o=i[t.getColorRepresentation().toLowerCase()];if(o){var a=o[n],c=e+(a>=100?1e3*r:r);return c<=0?0:Number((c<a?c:a).toPrecision(3))}return e}))}if(r.autoReposition&&!r.inline){var a=null,c=this;n.push(u(window,["scroll","resize"],(function(){c.isOpen()&&(r.closeOnScroll&&c.hide(),null===a?(a=setTimeout((function(){return a=null}),100),requestAnimationFrame((function t(){c._rePositioningPicker(),null!==a&&requestAnimationFrame(t)}))):(clearTimeout(a),a=setTimeout((function(){return a=null}),100)))}),{capture:!0}))}this._eventBindings=n},r._rePositioningPicker=function(){var t=this.options;if(!t.inline&&!this._nanopop.update({container:document.body.getBoundingClientRect(),position:t.position})){var e=this._root.app,r=e.getBoundingClientRect();e.style.top=(window.innerHeight-r.height)/2+"px",e.style.left=(window.innerWidth-r.width)/2+"px"}},r._updateOutput=function(t){var e=this._root,r=this._color,n=this.options;if(e.interaction.type()){var o="to"+e.interaction.type().getAttribute("data-type");e.interaction.result.value="function"==typeof r[o]?r[o]().toString(n.outputPrecision):""}!this._initializingActive&&this._recalc&&this._emit("change",r,t,this)},r._clearColor=function(){var t=arguments.length>0&&void 0!==arguments[0]&&arguments[0],e=this._root,r=this.options;r.useAsButton||e.button.style.setProperty("--pcr-color","rgba(0, 0, 0, 0.15)"),e.button.classList.add("clear"),r.showAlways||this.hide(),this._lastColor=null,this._initializingActive||t||(this._emit("save",null),this._emit("clear"))},r._parseLocalColor=function(t){var e=P(t),r=e.values,n=e.type,o=e.a,i=this.options.lockOpacity,a=void 0!==o&&1!==o;return r&&3===r.length&&(r[3]=void 0),{values:!r||i&&a?null:r,type:n}},r._t=function(t){return this.options.i18n[t]||e.I18N_DEFAULTS[t]},r._emit=function(t){for(var e=this,r=arguments.length,n=new Array(r>1?r-1:0),o=1;o<r;o++)n[o-1]=arguments[o];this._eventListener[t].forEach((function(t){return t.apply(void 0,n.concat([e]))}))},r.on=function(t,e){return this._eventListener[t].push(e),this},r.off=function(t,e){var r=this._eventListener[t]||[],n=r.indexOf(e);return~n&&r.splice(n,1),this},r.addSwatch=function(t){var e=this,r=this._parseLocalColor(t).values;if(r){var n=this._swatchColors,o=this._root,i=k.apply(void 0,r),a=p('<button type="button" style="--pcr-color: '+i.toRGBA().toString(0)+'" aria-label="'+this._t("btn:swatch")+'"/>');return o.swatches.appendChild(a),n.push({el:a,color:i}),this._eventBindings.push(u(a,"click",(function(){e.setHSVA.apply(e,i.toHSVA().concat([!0])),e._emit("swatchselect",i),e._emit("change",i,"swatch",e)}))),!0}return!1},r.removeSwatch=function(t){var e=this._swatchColors[t];if(e){var r=e.el;return this._root.swatches.removeChild(r),this._swatchColors.splice(t,1),!0}return!1},r.applyColor=function(){var t=arguments.length>0&&void 0!==arguments[0]&&arguments[0],e=this._root,r=e.preview,n=e.button,o=this._color.toRGBA().toString(0);return r.lastColor.style.setProperty("--pcr-color",o),this.options.useAsButton||n.style.setProperty("--pcr-color",o),n.classList.remove("clear"),this._lastColor=this._color.clone(),this._initializingActive||t||this._emit("save",this._color),this},r.destroy=function(){var e=this;cancelAnimationFrame(this._setupAnimationFrame),this._eventBindings.forEach((function(e){return l.apply(t,e)})),Object.keys(this._components).forEach((function(t){return e._components[t].destroy()}))},r.destroyAndRemove=function(){var t=this;this.destroy();var e=this._root,r=e.root,n=e.app;r.parentElement&&r.parentElement.removeChild(r),n.parentElement.removeChild(n),Object.keys(this).forEach((function(e){return t[e]=null}))},r.hide=function(){return!!this.isOpen()&&(this._root.app.classList.remove("visible"),this._emit("hide"),!0)},r.show=function(){return!this.options.disabled&&!this.isOpen()&&(this._root.app.classList.add("visible"),this._rePositioningPicker(),this._emit("show",this._color),this)},r.isOpen=function(){return this._root.app.classList.contains("visible")},r.setHSVA=function(){var t=arguments.length>0&&void 0!==arguments[0]?arguments[0]:360,e=arguments.length>1&&void 0!==arguments[1]?arguments[1]:0,r=arguments.length>2&&void 0!==arguments[2]?arguments[2]:0,n=arguments.length>3&&void 0!==arguments[3]?arguments[3]:1,o=arguments.length>4&&void 0!==arguments[4]&&arguments[4],i=this._recalc;if(this._recalc=!1,t<0||t>360||e<0||e>100||r<0||r>100||n<0||n>1)return!1;this._color=k(t,e,r,n);var a=this._components,c=a.hue,s=a.opacity,u=a.palette;return c.update(t/360),s.update(n),u.update(e/100,1-r/100),o||this.applyColor(),i&&this._updateOutput(),this._recalc=i,!0},r.setColor=function(t){var e=arguments.length>1&&void 0!==arguments[1]&&arguments[1];if(null===t)return this._clearColor(e),!0;var r=this._parseLocalColor(t),n=r.values,o=r.type;if(n){var i=o.toUpperCase(),a=this._root.interaction.options,c=a.find((function(t){return t.getAttribute("data-type")===i}));if(c&&!c.hidden)for(var s,u=H(a);!(s=u()).done;){var l=s.value;l.classList[l===c?"add":"remove"]("active")}return!!this.setHSVA.apply(this,n.concat([e]))&&this.setColorRepresentation(i)}return!1},r.setColorRepresentation=function(t){return t=t.toUpperCase(),!!this._root.interaction.options.find((function(e){return e.getAttribute("data-type").startsWith(t)&&!e.click()}))},r.getColorRepresentation=function(){return this._representation},r.getColor=function(){return this._color},r.getSelectedColor=function(){return this._lastColor},r.getRoot=function(){return this._root},r.disable=function(){return this.hide(),this.options.disabled=!0,this._root.button.classList.add("disabled"),this},r.enable=function(){return this.options.disabled=!1,this._root.button.classList.remove("disabled"),this},e}();V(G,"utils",t),V(G,"version","1.8.2"),V(G,"I18N_DEFAULTS",{"ui:dialog":"color picker dialog","btn:toggle":"toggle color picker dialog","btn:swatch":"color swatch","btn:last-color":"use previous color","btn:save":"Save","btn:cancel":"Cancel","btn:clear":"Clear","aria:btn:save":"save and close","aria:btn:cancel":"cancel and close","aria:btn:clear":"clear and close","aria:input":"color input field","aria:palette":"color selection area","aria:hue":"hue selection slider","aria:opacity":"selection slider"}),V(G,"DEFAULT_OPTIONS",{appClass:null,theme:"classic",useAsButton:!1,padding:8,disabled:!1,comparison:!0,closeOnScroll:!1,outputPrecision:0,lockOpacity:!1,autoReposition:!0,container:"body",components:{interaction:{}},i18n:{},swatches:null,inline:!1,sliders:null,default:"#42445a",defaultRepresentation:null,position:"bottom-middle",adjustableNumbers:!0,showAlways:!1,closeWithKey:"Escape"}),V(G,"create",(function(t){return new G(t)}))})(),n=n.default})()}));
/**
 * @popperjs/core v2.11.5 - MIT License
 */

!function(e,t){"object"==typeof exports&&"undefined"!=typeof module?t(exports):"function"==typeof define&&define.amd?define(["exports"],t):t((e="undefined"!=typeof globalThis?globalThis:e||self).Popper={})}(this,(function(e){"use strict";function t(e){if(null==e)return window;if("[object Window]"!==e.toString()){var t=e.ownerDocument;return t&&t.defaultView||window}return e}function n(e){return e instanceof t(e).Element||e instanceof Element}function r(e){return e instanceof t(e).HTMLElement||e instanceof HTMLElement}function o(e){return"undefined"!=typeof ShadowRoot&&(e instanceof t(e).ShadowRoot||e instanceof ShadowRoot)}var i=Math.max,a=Math.min,s=Math.round;function f(e,t){void 0===t&&(t=!1);var n=e.getBoundingClientRect(),o=1,i=1;if(r(e)&&t){var a=e.offsetHeight,f=e.offsetWidth;f>0&&(o=s(n.width)/f||1),a>0&&(i=s(n.height)/a||1)}return{width:n.width/o,height:n.height/i,top:n.top/i,right:n.right/o,bottom:n.bottom/i,left:n.left/o,x:n.left/o,y:n.top/i}}function c(e){var n=t(e);return{scrollLeft:n.pageXOffset,scrollTop:n.pageYOffset}}function p(e){return e?(e.nodeName||"").toLowerCase():null}function u(e){return((n(e)?e.ownerDocument:e.document)||window.document).documentElement}function l(e){return f(u(e)).left+c(e).scrollLeft}function d(e){return t(e).getComputedStyle(e)}function h(e){var t=d(e),n=t.overflow,r=t.overflowX,o=t.overflowY;return/auto|scroll|overlay|hidden/.test(n+o+r)}function m(e,n,o){void 0===o&&(o=!1);var i,a,d=r(n),m=r(n)&&function(e){var t=e.getBoundingClientRect(),n=s(t.width)/e.offsetWidth||1,r=s(t.height)/e.offsetHeight||1;return 1!==n||1!==r}(n),v=u(n),g=f(e,m),y={scrollLeft:0,scrollTop:0},b={x:0,y:0};return(d||!d&&!o)&&(("body"!==p(n)||h(v))&&(y=(i=n)!==t(i)&&r(i)?{scrollLeft:(a=i).scrollLeft,scrollTop:a.scrollTop}:c(i)),r(n)?((b=f(n,!0)).x+=n.clientLeft,b.y+=n.clientTop):v&&(b.x=l(v))),{x:g.left+y.scrollLeft-b.x,y:g.top+y.scrollTop-b.y,width:g.width,height:g.height}}function v(e){var t=f(e),n=e.offsetWidth,r=e.offsetHeight;return Math.abs(t.width-n)<=1&&(n=t.width),Math.abs(t.height-r)<=1&&(r=t.height),{x:e.offsetLeft,y:e.offsetTop,width:n,height:r}}function g(e){return"html"===p(e)?e:e.assignedSlot||e.parentNode||(o(e)?e.host:null)||u(e)}function y(e){return["html","body","#document"].indexOf(p(e))>=0?e.ownerDocument.body:r(e)&&h(e)?e:y(g(e))}function b(e,n){var r;void 0===n&&(n=[]);var o=y(e),i=o===(null==(r=e.ownerDocument)?void 0:r.body),a=t(o),s=i?[a].concat(a.visualViewport||[],h(o)?o:[]):o,f=n.concat(s);return i?f:f.concat(b(g(s)))}function x(e){return["table","td","th"].indexOf(p(e))>=0}function w(e){return r(e)&&"fixed"!==d(e).position?e.offsetParent:null}function O(e){for(var n=t(e),i=w(e);i&&x(i)&&"static"===d(i).position;)i=w(i);return i&&("html"===p(i)||"body"===p(i)&&"static"===d(i).position)?n:i||function(e){var t=-1!==navigator.userAgent.toLowerCase().indexOf("firefox");if(-1!==navigator.userAgent.indexOf("Trident")&&r(e)&&"fixed"===d(e).position)return null;var n=g(e);for(o(n)&&(n=n.host);r(n)&&["html","body"].indexOf(p(n))<0;){var i=d(n);if("none"!==i.transform||"none"!==i.perspective||"paint"===i.contain||-1!==["transform","perspective"].indexOf(i.willChange)||t&&"filter"===i.willChange||t&&i.filter&&"none"!==i.filter)return n;n=n.parentNode}return null}(e)||n}var j="top",E="bottom",D="right",A="left",L="auto",P=[j,E,D,A],M="start",k="end",W="viewport",B="popper",H=P.reduce((function(e,t){return e.concat([t+"-"+M,t+"-"+k])}),[]),T=[].concat(P,[L]).reduce((function(e,t){return e.concat([t,t+"-"+M,t+"-"+k])}),[]),R=["beforeRead","read","afterRead","beforeMain","main","afterMain","beforeWrite","write","afterWrite"];function S(e){var t=new Map,n=new Set,r=[];function o(e){n.add(e.name),[].concat(e.requires||[],e.requiresIfExists||[]).forEach((function(e){if(!n.has(e)){var r=t.get(e);r&&o(r)}})),r.push(e)}return e.forEach((function(e){t.set(e.name,e)})),e.forEach((function(e){n.has(e.name)||o(e)})),r}function C(e){return e.split("-")[0]}function q(e,t){var n=t.getRootNode&&t.getRootNode();if(e.contains(t))return!0;if(n&&o(n)){var r=t;do{if(r&&e.isSameNode(r))return!0;r=r.parentNode||r.host}while(r)}return!1}function V(e){return Object.assign({},e,{left:e.x,top:e.y,right:e.x+e.width,bottom:e.y+e.height})}function N(e,r){return r===W?V(function(e){var n=t(e),r=u(e),o=n.visualViewport,i=r.clientWidth,a=r.clientHeight,s=0,f=0;return o&&(i=o.width,a=o.height,/^((?!chrome|android).)*safari/i.test(navigator.userAgent)||(s=o.offsetLeft,f=o.offsetTop)),{width:i,height:a,x:s+l(e),y:f}}(e)):n(r)?function(e){var t=f(e);return t.top=t.top+e.clientTop,t.left=t.left+e.clientLeft,t.bottom=t.top+e.clientHeight,t.right=t.left+e.clientWidth,t.width=e.clientWidth,t.height=e.clientHeight,t.x=t.left,t.y=t.top,t}(r):V(function(e){var t,n=u(e),r=c(e),o=null==(t=e.ownerDocument)?void 0:t.body,a=i(n.scrollWidth,n.clientWidth,o?o.scrollWidth:0,o?o.clientWidth:0),s=i(n.scrollHeight,n.clientHeight,o?o.scrollHeight:0,o?o.clientHeight:0),f=-r.scrollLeft+l(e),p=-r.scrollTop;return"rtl"===d(o||n).direction&&(f+=i(n.clientWidth,o?o.clientWidth:0)-a),{width:a,height:s,x:f,y:p}}(u(e)))}function I(e,t,o){var s="clippingParents"===t?function(e){var t=b(g(e)),o=["absolute","fixed"].indexOf(d(e).position)>=0&&r(e)?O(e):e;return n(o)?t.filter((function(e){return n(e)&&q(e,o)&&"body"!==p(e)})):[]}(e):[].concat(t),f=[].concat(s,[o]),c=f[0],u=f.reduce((function(t,n){var r=N(e,n);return t.top=i(r.top,t.top),t.right=a(r.right,t.right),t.bottom=a(r.bottom,t.bottom),t.left=i(r.left,t.left),t}),N(e,c));return u.width=u.right-u.left,u.height=u.bottom-u.top,u.x=u.left,u.y=u.top,u}function _(e){return e.split("-")[1]}function F(e){return["top","bottom"].indexOf(e)>=0?"x":"y"}function U(e){var t,n=e.reference,r=e.element,o=e.placement,i=o?C(o):null,a=o?_(o):null,s=n.x+n.width/2-r.width/2,f=n.y+n.height/2-r.height/2;switch(i){case j:t={x:s,y:n.y-r.height};break;case E:t={x:s,y:n.y+n.height};break;case D:t={x:n.x+n.width,y:f};break;case A:t={x:n.x-r.width,y:f};break;default:t={x:n.x,y:n.y}}var c=i?F(i):null;if(null!=c){var p="y"===c?"height":"width";switch(a){case M:t[c]=t[c]-(n[p]/2-r[p]/2);break;case k:t[c]=t[c]+(n[p]/2-r[p]/2)}}return t}function z(e){return Object.assign({},{top:0,right:0,bottom:0,left:0},e)}function X(e,t){return t.reduce((function(t,n){return t[n]=e,t}),{})}function Y(e,t){void 0===t&&(t={});var r=t,o=r.placement,i=void 0===o?e.placement:o,a=r.boundary,s=void 0===a?"clippingParents":a,c=r.rootBoundary,p=void 0===c?W:c,l=r.elementContext,d=void 0===l?B:l,h=r.altBoundary,m=void 0!==h&&h,v=r.padding,g=void 0===v?0:v,y=z("number"!=typeof g?g:X(g,P)),b=d===B?"reference":B,x=e.rects.popper,w=e.elements[m?b:d],O=I(n(w)?w:w.contextElement||u(e.elements.popper),s,p),A=f(e.elements.reference),L=U({reference:A,element:x,strategy:"absolute",placement:i}),M=V(Object.assign({},x,L)),k=d===B?M:A,H={top:O.top-k.top+y.top,bottom:k.bottom-O.bottom+y.bottom,left:O.left-k.left+y.left,right:k.right-O.right+y.right},T=e.modifiersData.offset;if(d===B&&T){var R=T[i];Object.keys(H).forEach((function(e){var t=[D,E].indexOf(e)>=0?1:-1,n=[j,E].indexOf(e)>=0?"y":"x";H[e]+=R[n]*t}))}return H}var G={placement:"bottom",modifiers:[],strategy:"absolute"};function J(){for(var e=arguments.length,t=new Array(e),n=0;n<e;n++)t[n]=arguments[n];return!t.some((function(e){return!(e&&"function"==typeof e.getBoundingClientRect)}))}function K(e){void 0===e&&(e={});var t=e,r=t.defaultModifiers,o=void 0===r?[]:r,i=t.defaultOptions,a=void 0===i?G:i;return function(e,t,r){void 0===r&&(r=a);var i,s,f={placement:"bottom",orderedModifiers:[],options:Object.assign({},G,a),modifiersData:{},elements:{reference:e,popper:t},attributes:{},styles:{}},c=[],p=!1,u={state:f,setOptions:function(r){var i="function"==typeof r?r(f.options):r;l(),f.options=Object.assign({},a,f.options,i),f.scrollParents={reference:n(e)?b(e):e.contextElement?b(e.contextElement):[],popper:b(t)};var s,p,d=function(e){var t=S(e);return R.reduce((function(e,n){return e.concat(t.filter((function(e){return e.phase===n})))}),[])}((s=[].concat(o,f.options.modifiers),p=s.reduce((function(e,t){var n=e[t.name];return e[t.name]=n?Object.assign({},n,t,{options:Object.assign({},n.options,t.options),data:Object.assign({},n.data,t.data)}):t,e}),{}),Object.keys(p).map((function(e){return p[e]}))));return f.orderedModifiers=d.filter((function(e){return e.enabled})),f.orderedModifiers.forEach((function(e){var t=e.name,n=e.options,r=void 0===n?{}:n,o=e.effect;if("function"==typeof o){var i=o({state:f,name:t,instance:u,options:r}),a=function(){};c.push(i||a)}})),u.update()},forceUpdate:function(){if(!p){var e=f.elements,t=e.reference,n=e.popper;if(J(t,n)){f.rects={reference:m(t,O(n),"fixed"===f.options.strategy),popper:v(n)},f.reset=!1,f.placement=f.options.placement,f.orderedModifiers.forEach((function(e){return f.modifiersData[e.name]=Object.assign({},e.data)}));for(var r=0;r<f.orderedModifiers.length;r++)if(!0!==f.reset){var o=f.orderedModifiers[r],i=o.fn,a=o.options,s=void 0===a?{}:a,c=o.name;"function"==typeof i&&(f=i({state:f,options:s,name:c,instance:u})||f)}else f.reset=!1,r=-1}}},update:(i=function(){return new Promise((function(e){u.forceUpdate(),e(f)}))},function(){return s||(s=new Promise((function(e){Promise.resolve().then((function(){s=void 0,e(i())}))}))),s}),destroy:function(){l(),p=!0}};if(!J(e,t))return u;function l(){c.forEach((function(e){return e()})),c=[]}return u.setOptions(r).then((function(e){!p&&r.onFirstUpdate&&r.onFirstUpdate(e)})),u}}var Q={passive:!0};var Z={name:"eventListeners",enabled:!0,phase:"write",fn:function(){},effect:function(e){var n=e.state,r=e.instance,o=e.options,i=o.scroll,a=void 0===i||i,s=o.resize,f=void 0===s||s,c=t(n.elements.popper),p=[].concat(n.scrollParents.reference,n.scrollParents.popper);return a&&p.forEach((function(e){e.addEventListener("scroll",r.update,Q)})),f&&c.addEventListener("resize",r.update,Q),function(){a&&p.forEach((function(e){e.removeEventListener("scroll",r.update,Q)})),f&&c.removeEventListener("resize",r.update,Q)}},data:{}};var $={name:"popperOffsets",enabled:!0,phase:"read",fn:function(e){var t=e.state,n=e.name;t.modifiersData[n]=U({reference:t.rects.reference,element:t.rects.popper,strategy:"absolute",placement:t.placement})},data:{}},ee={top:"auto",right:"auto",bottom:"auto",left:"auto"};function te(e){var n,r=e.popper,o=e.popperRect,i=e.placement,a=e.variation,f=e.offsets,c=e.position,p=e.gpuAcceleration,l=e.adaptive,h=e.roundOffsets,m=e.isFixed,v=f.x,g=void 0===v?0:v,y=f.y,b=void 0===y?0:y,x="function"==typeof h?h({x:g,y:b}):{x:g,y:b};g=x.x,b=x.y;var w=f.hasOwnProperty("x"),L=f.hasOwnProperty("y"),P=A,M=j,W=window;if(l){var B=O(r),H="clientHeight",T="clientWidth";if(B===t(r)&&"static"!==d(B=u(r)).position&&"absolute"===c&&(H="scrollHeight",T="scrollWidth"),B=B,i===j||(i===A||i===D)&&a===k)M=E,b-=(m&&B===W&&W.visualViewport?W.visualViewport.height:B[H])-o.height,b*=p?1:-1;if(i===A||(i===j||i===E)&&a===k)P=D,g-=(m&&B===W&&W.visualViewport?W.visualViewport.width:B[T])-o.width,g*=p?1:-1}var R,S=Object.assign({position:c},l&&ee),C=!0===h?function(e){var t=e.x,n=e.y,r=window.devicePixelRatio||1;return{x:s(t*r)/r||0,y:s(n*r)/r||0}}({x:g,y:b}):{x:g,y:b};return g=C.x,b=C.y,p?Object.assign({},S,((R={})[M]=L?"0":"",R[P]=w?"0":"",R.transform=(W.devicePixelRatio||1)<=1?"translate("+g+"px, "+b+"px)":"translate3d("+g+"px, "+b+"px, 0)",R)):Object.assign({},S,((n={})[M]=L?b+"px":"",n[P]=w?g+"px":"",n.transform="",n))}var ne={name:"computeStyles",enabled:!0,phase:"beforeWrite",fn:function(e){var t=e.state,n=e.options,r=n.gpuAcceleration,o=void 0===r||r,i=n.adaptive,a=void 0===i||i,s=n.roundOffsets,f=void 0===s||s,c={placement:C(t.placement),variation:_(t.placement),popper:t.elements.popper,popperRect:t.rects.popper,gpuAcceleration:o,isFixed:"fixed"===t.options.strategy};null!=t.modifiersData.popperOffsets&&(t.styles.popper=Object.assign({},t.styles.popper,te(Object.assign({},c,{offsets:t.modifiersData.popperOffsets,position:t.options.strategy,adaptive:a,roundOffsets:f})))),null!=t.modifiersData.arrow&&(t.styles.arrow=Object.assign({},t.styles.arrow,te(Object.assign({},c,{offsets:t.modifiersData.arrow,position:"absolute",adaptive:!1,roundOffsets:f})))),t.attributes.popper=Object.assign({},t.attributes.popper,{"data-popper-placement":t.placement})},data:{}};var re={name:"applyStyles",enabled:!0,phase:"write",fn:function(e){var t=e.state;Object.keys(t.elements).forEach((function(e){var n=t.styles[e]||{},o=t.attributes[e]||{},i=t.elements[e];r(i)&&p(i)&&(Object.assign(i.style,n),Object.keys(o).forEach((function(e){var t=o[e];!1===t?i.removeAttribute(e):i.setAttribute(e,!0===t?"":t)})))}))},effect:function(e){var t=e.state,n={popper:{position:t.options.strategy,left:"0",top:"0",margin:"0"},arrow:{position:"absolute"},reference:{}};return Object.assign(t.elements.popper.style,n.popper),t.styles=n,t.elements.arrow&&Object.assign(t.elements.arrow.style,n.arrow),function(){Object.keys(t.elements).forEach((function(e){var o=t.elements[e],i=t.attributes[e]||{},a=Object.keys(t.styles.hasOwnProperty(e)?t.styles[e]:n[e]).reduce((function(e,t){return e[t]="",e}),{});r(o)&&p(o)&&(Object.assign(o.style,a),Object.keys(i).forEach((function(e){o.removeAttribute(e)})))}))}},requires:["computeStyles"]};var oe={name:"offset",enabled:!0,phase:"main",requires:["popperOffsets"],fn:function(e){var t=e.state,n=e.options,r=e.name,o=n.offset,i=void 0===o?[0,0]:o,a=T.reduce((function(e,n){return e[n]=function(e,t,n){var r=C(e),o=[A,j].indexOf(r)>=0?-1:1,i="function"==typeof n?n(Object.assign({},t,{placement:e})):n,a=i[0],s=i[1];return a=a||0,s=(s||0)*o,[A,D].indexOf(r)>=0?{x:s,y:a}:{x:a,y:s}}(n,t.rects,i),e}),{}),s=a[t.placement],f=s.x,c=s.y;null!=t.modifiersData.popperOffsets&&(t.modifiersData.popperOffsets.x+=f,t.modifiersData.popperOffsets.y+=c),t.modifiersData[r]=a}},ie={left:"right",right:"left",bottom:"top",top:"bottom"};function ae(e){return e.replace(/left|right|bottom|top/g,(function(e){return ie[e]}))}var se={start:"end",end:"start"};function fe(e){return e.replace(/start|end/g,(function(e){return se[e]}))}function ce(e,t){void 0===t&&(t={});var n=t,r=n.placement,o=n.boundary,i=n.rootBoundary,a=n.padding,s=n.flipVariations,f=n.allowedAutoPlacements,c=void 0===f?T:f,p=_(r),u=p?s?H:H.filter((function(e){return _(e)===p})):P,l=u.filter((function(e){return c.indexOf(e)>=0}));0===l.length&&(l=u);var d=l.reduce((function(t,n){return t[n]=Y(e,{placement:n,boundary:o,rootBoundary:i,padding:a})[C(n)],t}),{});return Object.keys(d).sort((function(e,t){return d[e]-d[t]}))}var pe={name:"flip",enabled:!0,phase:"main",fn:function(e){var t=e.state,n=e.options,r=e.name;if(!t.modifiersData[r]._skip){for(var o=n.mainAxis,i=void 0===o||o,a=n.altAxis,s=void 0===a||a,f=n.fallbackPlacements,c=n.padding,p=n.boundary,u=n.rootBoundary,l=n.altBoundary,d=n.flipVariations,h=void 0===d||d,m=n.allowedAutoPlacements,v=t.options.placement,g=C(v),y=f||(g===v||!h?[ae(v)]:function(e){if(C(e)===L)return[];var t=ae(e);return[fe(e),t,fe(t)]}(v)),b=[v].concat(y).reduce((function(e,n){return e.concat(C(n)===L?ce(t,{placement:n,boundary:p,rootBoundary:u,padding:c,flipVariations:h,allowedAutoPlacements:m}):n)}),[]),x=t.rects.reference,w=t.rects.popper,O=new Map,P=!0,k=b[0],W=0;W<b.length;W++){var B=b[W],H=C(B),T=_(B)===M,R=[j,E].indexOf(H)>=0,S=R?"width":"height",q=Y(t,{placement:B,boundary:p,rootBoundary:u,altBoundary:l,padding:c}),V=R?T?D:A:T?E:j;x[S]>w[S]&&(V=ae(V));var N=ae(V),I=[];if(i&&I.push(q[H]<=0),s&&I.push(q[V]<=0,q[N]<=0),I.every((function(e){return e}))){k=B,P=!1;break}O.set(B,I)}if(P)for(var F=function(e){var t=b.find((function(t){var n=O.get(t);if(n)return n.slice(0,e).every((function(e){return e}))}));if(t)return k=t,"break"},U=h?3:1;U>0;U--){if("break"===F(U))break}t.placement!==k&&(t.modifiersData[r]._skip=!0,t.placement=k,t.reset=!0)}},requiresIfExists:["offset"],data:{_skip:!1}};function ue(e,t,n){return i(e,a(t,n))}var le={name:"preventOverflow",enabled:!0,phase:"main",fn:function(e){var t=e.state,n=e.options,r=e.name,o=n.mainAxis,s=void 0===o||o,f=n.altAxis,c=void 0!==f&&f,p=n.boundary,u=n.rootBoundary,l=n.altBoundary,d=n.padding,h=n.tether,m=void 0===h||h,g=n.tetherOffset,y=void 0===g?0:g,b=Y(t,{boundary:p,rootBoundary:u,padding:d,altBoundary:l}),x=C(t.placement),w=_(t.placement),L=!w,P=F(x),k="x"===P?"y":"x",W=t.modifiersData.popperOffsets,B=t.rects.reference,H=t.rects.popper,T="function"==typeof y?y(Object.assign({},t.rects,{placement:t.placement})):y,R="number"==typeof T?{mainAxis:T,altAxis:T}:Object.assign({mainAxis:0,altAxis:0},T),S=t.modifiersData.offset?t.modifiersData.offset[t.placement]:null,q={x:0,y:0};if(W){if(s){var V,N="y"===P?j:A,I="y"===P?E:D,U="y"===P?"height":"width",z=W[P],X=z+b[N],G=z-b[I],J=m?-H[U]/2:0,K=w===M?B[U]:H[U],Q=w===M?-H[U]:-B[U],Z=t.elements.arrow,$=m&&Z?v(Z):{width:0,height:0},ee=t.modifiersData["arrow#persistent"]?t.modifiersData["arrow#persistent"].padding:{top:0,right:0,bottom:0,left:0},te=ee[N],ne=ee[I],re=ue(0,B[U],$[U]),oe=L?B[U]/2-J-re-te-R.mainAxis:K-re-te-R.mainAxis,ie=L?-B[U]/2+J+re+ne+R.mainAxis:Q+re+ne+R.mainAxis,ae=t.elements.arrow&&O(t.elements.arrow),se=ae?"y"===P?ae.clientTop||0:ae.clientLeft||0:0,fe=null!=(V=null==S?void 0:S[P])?V:0,ce=z+ie-fe,pe=ue(m?a(X,z+oe-fe-se):X,z,m?i(G,ce):G);W[P]=pe,q[P]=pe-z}if(c){var le,de="x"===P?j:A,he="x"===P?E:D,me=W[k],ve="y"===k?"height":"width",ge=me+b[de],ye=me-b[he],be=-1!==[j,A].indexOf(x),xe=null!=(le=null==S?void 0:S[k])?le:0,we=be?ge:me-B[ve]-H[ve]-xe+R.altAxis,Oe=be?me+B[ve]+H[ve]-xe-R.altAxis:ye,je=m&&be?function(e,t,n){var r=ue(e,t,n);return r>n?n:r}(we,me,Oe):ue(m?we:ge,me,m?Oe:ye);W[k]=je,q[k]=je-me}t.modifiersData[r]=q}},requiresIfExists:["offset"]};var de={name:"arrow",enabled:!0,phase:"main",fn:function(e){var t,n=e.state,r=e.name,o=e.options,i=n.elements.arrow,a=n.modifiersData.popperOffsets,s=C(n.placement),f=F(s),c=[A,D].indexOf(s)>=0?"height":"width";if(i&&a){var p=function(e,t){return z("number"!=typeof(e="function"==typeof e?e(Object.assign({},t.rects,{placement:t.placement})):e)?e:X(e,P))}(o.padding,n),u=v(i),l="y"===f?j:A,d="y"===f?E:D,h=n.rects.reference[c]+n.rects.reference[f]-a[f]-n.rects.popper[c],m=a[f]-n.rects.reference[f],g=O(i),y=g?"y"===f?g.clientHeight||0:g.clientWidth||0:0,b=h/2-m/2,x=p[l],w=y-u[c]-p[d],L=y/2-u[c]/2+b,M=ue(x,L,w),k=f;n.modifiersData[r]=((t={})[k]=M,t.centerOffset=M-L,t)}},effect:function(e){var t=e.state,n=e.options.element,r=void 0===n?"[data-popper-arrow]":n;null!=r&&("string"!=typeof r||(r=t.elements.popper.querySelector(r)))&&q(t.elements.popper,r)&&(t.elements.arrow=r)},requires:["popperOffsets"],requiresIfExists:["preventOverflow"]};function he(e,t,n){return void 0===n&&(n={x:0,y:0}),{top:e.top-t.height-n.y,right:e.right-t.width+n.x,bottom:e.bottom-t.height+n.y,left:e.left-t.width-n.x}}function me(e){return[j,D,E,A].some((function(t){return e[t]>=0}))}var ve={name:"hide",enabled:!0,phase:"main",requiresIfExists:["preventOverflow"],fn:function(e){var t=e.state,n=e.name,r=t.rects.reference,o=t.rects.popper,i=t.modifiersData.preventOverflow,a=Y(t,{elementContext:"reference"}),s=Y(t,{altBoundary:!0}),f=he(a,r),c=he(s,o,i),p=me(f),u=me(c);t.modifiersData[n]={referenceClippingOffsets:f,popperEscapeOffsets:c,isReferenceHidden:p,hasPopperEscaped:u},t.attributes.popper=Object.assign({},t.attributes.popper,{"data-popper-reference-hidden":p,"data-popper-escaped":u})}},ge=K({defaultModifiers:[Z,$,ne,re]}),ye=[Z,$,ne,re,oe,pe,le,de,ve],be=K({defaultModifiers:ye});e.applyStyles=re,e.arrow=de,e.computeStyles=ne,e.createPopper=be,e.createPopperLite=ge,e.defaultModifiers=ye,e.detectOverflow=Y,e.eventListeners=Z,e.flip=pe,e.hide=ve,e.offset=oe,e.popperGenerator=K,e.popperOffsets=$,e.preventOverflow=le,Object.defineProperty(e,"__esModule",{value:!0})}));
//# sourceMappingURL=popper.min.js.map
function swipedetect(el, callback){
  
    var touchsurface = el,
    swipedir,
    startX,
    startY,
    distX,
    distY,
    threshold = 100, //required min distance traveled to be considered swipe
    restraint = 150, // maximum distance allowed at the same time in perpendicular direction
    allowedTime = 300, // maximum time allowed to travel that distance
    elapsedTime,
    startTime,
    handleswipe = callback || function(swipedir){}
  
    touchsurface.addEventListener('touchstart', function(e){
        var touchobj = e.changedTouches[0]
        swipedir = 'none'
        dist = 0
        startX = touchobj.pageX
        startY = touchobj.pageY
        startTime = new Date().getTime() // record time when finger first makes contact with surface
        e.preventDefault()
    }, false)
  
    touchsurface.addEventListener('touchmove', function(e){
        e.preventDefault() // prevent scrolling when inside DIV
    }, false)
  
    touchsurface.addEventListener('touchend', function(e){
        var touchobj = e.changedTouches[0]
        distX = touchobj.pageX - startX // get horizontal dist traveled by finger while in contact with surface
        distY = touchobj.pageY - startY // get vertical dist traveled by finger while in contact with surface
        elapsedTime = new Date().getTime() - startTime // get time elapsed
        if (elapsedTime <= allowedTime){ // first condition for awipe met
            if (Math.abs(distX) >= threshold && Math.abs(distY) <= restraint){ // 2nd condition for horizontal swipe met
                swipedir = (distX < 0)? 'left' : 'right' // if dist traveled is negative, it indicates left swipe
            }
            else if (Math.abs(distY) >= threshold && Math.abs(distX) <= restraint){ // 2nd condition for vertical swipe met
                swipedir = (distY < 0)? 'up' : 'down' // if dist traveled is negative, it indicates up swipe
            }
        }
        handleswipe(swipedir)
        e.preventDefault()
    }, false)
}
!function(t,e){"object"==typeof exports&&"undefined"!=typeof module?module.exports=e(require("@popperjs/core")):"function"==typeof define&&define.amd?define(["@popperjs/core"],e):(t=t||self).tippy=e(t.Popper)}(this,(function(t){"use strict";var e="undefined"!=typeof window&&"undefined"!=typeof document,n=!!e&&!!window.msCrypto,r={passive:!0,capture:!0},o=function(){return document.body};function i(t,e,n){if(Array.isArray(t)){var r=t[e];return null==r?Array.isArray(n)?n[e]:n:r}return t}function a(t,e){var n={}.toString.call(t);return 0===n.indexOf("[object")&&n.indexOf(e+"]")>-1}function s(t,e){return"function"==typeof t?t.apply(void 0,e):t}function u(t,e){return 0===e?t:function(r){clearTimeout(n),n=setTimeout((function(){t(r)}),e)};var n}function p(t,e){var n=Object.assign({},t);return e.forEach((function(t){delete n[t]})),n}function c(t){return[].concat(t)}function f(t,e){-1===t.indexOf(e)&&t.push(e)}function l(t){return t.split("-")[0]}function d(t){return[].slice.call(t)}function v(t){return Object.keys(t).reduce((function(e,n){return void 0!==t[n]&&(e[n]=t[n]),e}),{})}function m(){return document.createElement("div")}function g(t){return["Element","Fragment"].some((function(e){return a(t,e)}))}function h(t){return a(t,"MouseEvent")}function b(t){return!(!t||!t._tippy||t._tippy.reference!==t)}function y(t){return g(t)?[t]:function(t){return a(t,"NodeList")}(t)?d(t):Array.isArray(t)?t:d(document.querySelectorAll(t))}function w(t,e){t.forEach((function(t){t&&(t.style.transitionDuration=e+"ms")}))}function x(t,e){t.forEach((function(t){t&&t.setAttribute("data-state",e)}))}function E(t){var e,n=c(t)[0];return null!=n&&null!=(e=n.ownerDocument)&&e.body?n.ownerDocument:document}function O(t,e,n){var r=e+"EventListener";["transitionend","webkitTransitionEnd"].forEach((function(e){t[r](e,n)}))}function C(t,e){for(var n=e;n;){var r;if(t.contains(n))return!0;n=null==n.getRootNode||null==(r=n.getRootNode())?void 0:r.host}return!1}var T={isTouch:!1},A=0;function L(){T.isTouch||(T.isTouch=!0,window.performance&&document.addEventListener("mousemove",D))}function D(){var t=performance.now();t-A<20&&(T.isTouch=!1,document.removeEventListener("mousemove",D)),A=t}function k(){var t=document.activeElement;if(b(t)){var e=t._tippy;t.blur&&!e.state.isVisible&&t.blur()}}var R=Object.assign({appendTo:o,aria:{content:"auto",expanded:"auto"},delay:0,duration:[300,250],getReferenceClientRect:null,hideOnClick:!0,ignoreAttributes:!1,interactive:!1,interactiveBorder:2,interactiveDebounce:0,moveTransition:"",offset:[0,10],onAfterUpdate:function(){},onBeforeUpdate:function(){},onCreate:function(){},onDestroy:function(){},onHidden:function(){},onHide:function(){},onMount:function(){},onShow:function(){},onShown:function(){},onTrigger:function(){},onUntrigger:function(){},onClickOutside:function(){},placement:"top",plugins:[],popperOptions:{},render:null,showOnCreate:!1,touch:!0,trigger:"mouseenter focus",triggerTarget:null},{animateFill:!1,followCursor:!1,inlinePositioning:!1,sticky:!1},{allowHTML:!1,animation:"fade",arrow:!0,content:"",inertia:!1,maxWidth:350,role:"tooltip",theme:"",zIndex:9999}),P=Object.keys(R);function j(t){var e=(t.plugins||[]).reduce((function(e,n){var r,o=n.name,i=n.defaultValue;o&&(e[o]=void 0!==t[o]?t[o]:null!=(r=R[o])?r:i);return e}),{});return Object.assign({},t,e)}function M(t,e){var n=Object.assign({},e,{content:s(e.content,[t])},e.ignoreAttributes?{}:function(t,e){return(e?Object.keys(j(Object.assign({},R,{plugins:e}))):P).reduce((function(e,n){var r=(t.getAttribute("data-tippy-"+n)||"").trim();if(!r)return e;if("content"===n)e[n]=r;else try{e[n]=JSON.parse(r)}catch(t){e[n]=r}return e}),{})}(t,e.plugins));return n.aria=Object.assign({},R.aria,n.aria),n.aria={expanded:"auto"===n.aria.expanded?e.interactive:n.aria.expanded,content:"auto"===n.aria.content?e.interactive?null:"describedby":n.aria.content},n}function V(t,e){t.innerHTML=e}function I(t){var e=m();return!0===t?e.className="tippy-arrow":(e.className="tippy-svg-arrow",g(t)?e.appendChild(t):V(e,t)),e}function S(t,e){g(e.content)?(V(t,""),t.appendChild(e.content)):"function"!=typeof e.content&&(e.allowHTML?V(t,e.content):t.textContent=e.content)}function B(t){var e=t.firstElementChild,n=d(e.children);return{box:e,content:n.find((function(t){return t.classList.contains("tippy-content")})),arrow:n.find((function(t){return t.classList.contains("tippy-arrow")||t.classList.contains("tippy-svg-arrow")})),backdrop:n.find((function(t){return t.classList.contains("tippy-backdrop")}))}}function N(t){var e=m(),n=m();n.className="tippy-box",n.setAttribute("data-state","hidden"),n.setAttribute("tabindex","-1");var r=m();function o(n,r){var o=B(e),i=o.box,a=o.content,s=o.arrow;r.theme?i.setAttribute("data-theme",r.theme):i.removeAttribute("data-theme"),"string"==typeof r.animation?i.setAttribute("data-animation",r.animation):i.removeAttribute("data-animation"),r.inertia?i.setAttribute("data-inertia",""):i.removeAttribute("data-inertia"),i.style.maxWidth="number"==typeof r.maxWidth?r.maxWidth+"px":r.maxWidth,r.role?i.setAttribute("role",r.role):i.removeAttribute("role"),n.content===r.content&&n.allowHTML===r.allowHTML||S(a,t.props),r.arrow?s?n.arrow!==r.arrow&&(i.removeChild(s),i.appendChild(I(r.arrow))):i.appendChild(I(r.arrow)):s&&i.removeChild(s)}return r.className="tippy-content",r.setAttribute("data-state","hidden"),S(r,t.props),e.appendChild(n),n.appendChild(r),o(t.props,t.props),{popper:e,onUpdate:o}}N.$$tippy=!0;var H=1,U=[],_=[];function z(e,a){var p,g,b,y,A,L,D,k,P=M(e,Object.assign({},R,j(v(a)))),V=!1,I=!1,S=!1,N=!1,z=[],F=u(wt,P.interactiveDebounce),W=H++,X=(k=P.plugins).filter((function(t,e){return k.indexOf(t)===e})),Y={id:W,reference:e,popper:m(),popperInstance:null,props:P,state:{isEnabled:!0,isVisible:!1,isDestroyed:!1,isMounted:!1,isShown:!1},plugins:X,clearDelayTimeouts:function(){clearTimeout(p),clearTimeout(g),cancelAnimationFrame(b)},setProps:function(t){if(Y.state.isDestroyed)return;at("onBeforeUpdate",[Y,t]),bt();var n=Y.props,r=M(e,Object.assign({},n,v(t),{ignoreAttributes:!0}));Y.props=r,ht(),n.interactiveDebounce!==r.interactiveDebounce&&(pt(),F=u(wt,r.interactiveDebounce));n.triggerTarget&&!r.triggerTarget?c(n.triggerTarget).forEach((function(t){t.removeAttribute("aria-expanded")})):r.triggerTarget&&e.removeAttribute("aria-expanded");ut(),it(),J&&J(n,r);Y.popperInstance&&(Ct(),At().forEach((function(t){requestAnimationFrame(t._tippy.popperInstance.forceUpdate)})));at("onAfterUpdate",[Y,t])},setContent:function(t){Y.setProps({content:t})},show:function(){var t=Y.state.isVisible,e=Y.state.isDestroyed,n=!Y.state.isEnabled,r=T.isTouch&&!Y.props.touch,a=i(Y.props.duration,0,R.duration);if(t||e||n||r)return;if(et().hasAttribute("disabled"))return;if(at("onShow",[Y],!1),!1===Y.props.onShow(Y))return;Y.state.isVisible=!0,tt()&&($.style.visibility="visible");it(),dt(),Y.state.isMounted||($.style.transition="none");if(tt()){var u=rt(),p=u.box,c=u.content;w([p,c],0)}L=function(){var t;if(Y.state.isVisible&&!N){if(N=!0,$.offsetHeight,$.style.transition=Y.props.moveTransition,tt()&&Y.props.animation){var e=rt(),n=e.box,r=e.content;w([n,r],a),x([n,r],"visible")}st(),ut(),f(_,Y),null==(t=Y.popperInstance)||t.forceUpdate(),at("onMount",[Y]),Y.props.animation&&tt()&&function(t,e){mt(t,e)}(a,(function(){Y.state.isShown=!0,at("onShown",[Y])}))}},function(){var t,e=Y.props.appendTo,n=et();t=Y.props.interactive&&e===o||"parent"===e?n.parentNode:s(e,[n]);t.contains($)||t.appendChild($);Y.state.isMounted=!0,Ct()}()},hide:function(){var t=!Y.state.isVisible,e=Y.state.isDestroyed,n=!Y.state.isEnabled,r=i(Y.props.duration,1,R.duration);if(t||e||n)return;if(at("onHide",[Y],!1),!1===Y.props.onHide(Y))return;Y.state.isVisible=!1,Y.state.isShown=!1,N=!1,V=!1,tt()&&($.style.visibility="hidden");if(pt(),vt(),it(!0),tt()){var o=rt(),a=o.box,s=o.content;Y.props.animation&&(w([a,s],r),x([a,s],"hidden"))}st(),ut(),Y.props.animation?tt()&&function(t,e){mt(t,(function(){!Y.state.isVisible&&$.parentNode&&$.parentNode.contains($)&&e()}))}(r,Y.unmount):Y.unmount()},hideWithInteractivity:function(t){nt().addEventListener("mousemove",F),f(U,F),F(t)},enable:function(){Y.state.isEnabled=!0},disable:function(){Y.hide(),Y.state.isEnabled=!1},unmount:function(){Y.state.isVisible&&Y.hide();if(!Y.state.isMounted)return;Tt(),At().forEach((function(t){t._tippy.unmount()})),$.parentNode&&$.parentNode.removeChild($);_=_.filter((function(t){return t!==Y})),Y.state.isMounted=!1,at("onHidden",[Y])},destroy:function(){if(Y.state.isDestroyed)return;Y.clearDelayTimeouts(),Y.unmount(),bt(),delete e._tippy,Y.state.isDestroyed=!0,at("onDestroy",[Y])}};if(!P.render)return Y;var q=P.render(Y),$=q.popper,J=q.onUpdate;$.setAttribute("data-tippy-root",""),$.id="tippy-"+Y.id,Y.popper=$,e._tippy=Y,$._tippy=Y;var G=X.map((function(t){return t.fn(Y)})),K=e.hasAttribute("aria-expanded");return ht(),ut(),it(),at("onCreate",[Y]),P.showOnCreate&&Lt(),$.addEventListener("mouseenter",(function(){Y.props.interactive&&Y.state.isVisible&&Y.clearDelayTimeouts()})),$.addEventListener("mouseleave",(function(){Y.props.interactive&&Y.props.trigger.indexOf("mouseenter")>=0&&nt().addEventListener("mousemove",F)})),Y;function Q(){var t=Y.props.touch;return Array.isArray(t)?t:[t,0]}function Z(){return"hold"===Q()[0]}function tt(){var t;return!(null==(t=Y.props.render)||!t.$$tippy)}function et(){return D||e}function nt(){var t=et().parentNode;return t?E(t):document}function rt(){return B($)}function ot(t){return Y.state.isMounted&&!Y.state.isVisible||T.isTouch||y&&"focus"===y.type?0:i(Y.props.delay,t?0:1,R.delay)}function it(t){void 0===t&&(t=!1),$.style.pointerEvents=Y.props.interactive&&!t?"":"none",$.style.zIndex=""+Y.props.zIndex}function at(t,e,n){var r;(void 0===n&&(n=!0),G.forEach((function(n){n[t]&&n[t].apply(n,e)})),n)&&(r=Y.props)[t].apply(r,e)}function st(){var t=Y.props.aria;if(t.content){var n="aria-"+t.content,r=$.id;c(Y.props.triggerTarget||e).forEach((function(t){var e=t.getAttribute(n);if(Y.state.isVisible)t.setAttribute(n,e?e+" "+r:r);else{var o=e&&e.replace(r,"").trim();o?t.setAttribute(n,o):t.removeAttribute(n)}}))}}function ut(){!K&&Y.props.aria.expanded&&c(Y.props.triggerTarget||e).forEach((function(t){Y.props.interactive?t.setAttribute("aria-expanded",Y.state.isVisible&&t===et()?"true":"false"):t.removeAttribute("aria-expanded")}))}function pt(){nt().removeEventListener("mousemove",F),U=U.filter((function(t){return t!==F}))}function ct(t){if(!T.isTouch||!S&&"mousedown"!==t.type){var n=t.composedPath&&t.composedPath()[0]||t.target;if(!Y.props.interactive||!C($,n)){if(c(Y.props.triggerTarget||e).some((function(t){return C(t,n)}))){if(T.isTouch)return;if(Y.state.isVisible&&Y.props.trigger.indexOf("click")>=0)return}else at("onClickOutside",[Y,t]);!0===Y.props.hideOnClick&&(Y.clearDelayTimeouts(),Y.hide(),I=!0,setTimeout((function(){I=!1})),Y.state.isMounted||vt())}}}function ft(){S=!0}function lt(){S=!1}function dt(){var t=nt();t.addEventListener("mousedown",ct,!0),t.addEventListener("touchend",ct,r),t.addEventListener("touchstart",lt,r),t.addEventListener("touchmove",ft,r)}function vt(){var t=nt();t.removeEventListener("mousedown",ct,!0),t.removeEventListener("touchend",ct,r),t.removeEventListener("touchstart",lt,r),t.removeEventListener("touchmove",ft,r)}function mt(t,e){var n=rt().box;function r(t){t.target===n&&(O(n,"remove",r),e())}if(0===t)return e();O(n,"remove",A),O(n,"add",r),A=r}function gt(t,n,r){void 0===r&&(r=!1),c(Y.props.triggerTarget||e).forEach((function(e){e.addEventListener(t,n,r),z.push({node:e,eventType:t,handler:n,options:r})}))}function ht(){var t;Z()&&(gt("touchstart",yt,{passive:!0}),gt("touchend",xt,{passive:!0})),(t=Y.props.trigger,t.split(/\s+/).filter(Boolean)).forEach((function(t){if("manual"!==t)switch(gt(t,yt),t){case"mouseenter":gt("mouseleave",xt);break;case"focus":gt(n?"focusout":"blur",Et);break;case"focusin":gt("focusout",Et)}}))}function bt(){z.forEach((function(t){var e=t.node,n=t.eventType,r=t.handler,o=t.options;e.removeEventListener(n,r,o)})),z=[]}function yt(t){var e,n=!1;if(Y.state.isEnabled&&!Ot(t)&&!I){var r="focus"===(null==(e=y)?void 0:e.type);y=t,D=t.currentTarget,ut(),!Y.state.isVisible&&h(t)&&U.forEach((function(e){return e(t)})),"click"===t.type&&(Y.props.trigger.indexOf("mouseenter")<0||V)&&!1!==Y.props.hideOnClick&&Y.state.isVisible?n=!0:Lt(t),"click"===t.type&&(V=!n),n&&!r&&Dt(t)}}function wt(t){var e=t.target,n=et().contains(e)||$.contains(e);"mousemove"===t.type&&n||function(t,e){var n=e.clientX,r=e.clientY;return t.every((function(t){var e=t.popperRect,o=t.popperState,i=t.props.interactiveBorder,a=l(o.placement),s=o.modifiersData.offset;if(!s)return!0;var u="bottom"===a?s.top.y:0,p="top"===a?s.bottom.y:0,c="right"===a?s.left.x:0,f="left"===a?s.right.x:0,d=e.top-r+u>i,v=r-e.bottom-p>i,m=e.left-n+c>i,g=n-e.right-f>i;return d||v||m||g}))}(At().concat($).map((function(t){var e,n=null==(e=t._tippy.popperInstance)?void 0:e.state;return n?{popperRect:t.getBoundingClientRect(),popperState:n,props:P}:null})).filter(Boolean),t)&&(pt(),Dt(t))}function xt(t){Ot(t)||Y.props.trigger.indexOf("click")>=0&&V||(Y.props.interactive?Y.hideWithInteractivity(t):Dt(t))}function Et(t){Y.props.trigger.indexOf("focusin")<0&&t.target!==et()||Y.props.interactive&&t.relatedTarget&&$.contains(t.relatedTarget)||Dt(t)}function Ot(t){return!!T.isTouch&&Z()!==t.type.indexOf("touch")>=0}function Ct(){Tt();var n=Y.props,r=n.popperOptions,o=n.placement,i=n.offset,a=n.getReferenceClientRect,s=n.moveTransition,u=tt()?B($).arrow:null,p=a?{getBoundingClientRect:a,contextElement:a.contextElement||et()}:e,c=[{name:"offset",options:{offset:i}},{name:"preventOverflow",options:{padding:{top:2,bottom:2,left:5,right:5}}},{name:"flip",options:{padding:5}},{name:"computeStyles",options:{adaptive:!s}},{name:"$$tippy",enabled:!0,phase:"beforeWrite",requires:["computeStyles"],fn:function(t){var e=t.state;if(tt()){var n=rt().box;["placement","reference-hidden","escaped"].forEach((function(t){"placement"===t?n.setAttribute("data-placement",e.placement):e.attributes.popper["data-popper-"+t]?n.setAttribute("data-"+t,""):n.removeAttribute("data-"+t)})),e.attributes.popper={}}}}];tt()&&u&&c.push({name:"arrow",options:{element:u,padding:3}}),c.push.apply(c,(null==r?void 0:r.modifiers)||[]),Y.popperInstance=t.createPopper(p,$,Object.assign({},r,{placement:o,onFirstUpdate:L,modifiers:c}))}function Tt(){Y.popperInstance&&(Y.popperInstance.destroy(),Y.popperInstance=null)}function At(){return d($.querySelectorAll("[data-tippy-root]"))}function Lt(t){Y.clearDelayTimeouts(),t&&at("onTrigger",[Y,t]),dt();var e=ot(!0),n=Q(),r=n[0],o=n[1];T.isTouch&&"hold"===r&&o&&(e=o),e?p=setTimeout((function(){Y.show()}),e):Y.show()}function Dt(t){if(Y.clearDelayTimeouts(),at("onUntrigger",[Y,t]),Y.state.isVisible){if(!(Y.props.trigger.indexOf("mouseenter")>=0&&Y.props.trigger.indexOf("click")>=0&&["mouseleave","mousemove"].indexOf(t.type)>=0&&V)){var e=ot(!1);e?g=setTimeout((function(){Y.state.isVisible&&Y.hide()}),e):b=requestAnimationFrame((function(){Y.hide()}))}}else vt()}}function F(t,e){void 0===e&&(e={});var n=R.plugins.concat(e.plugins||[]);document.addEventListener("touchstart",L,r),window.addEventListener("blur",k);var o=Object.assign({},e,{plugins:n}),i=y(t).reduce((function(t,e){var n=e&&z(e,o);return n&&t.push(n),t}),[]);return g(t)?i[0]:i}F.defaultProps=R,F.setDefaultProps=function(t){Object.keys(t).forEach((function(e){R[e]=t[e]}))},F.currentInput=T;var W=Object.assign({},t.applyStyles,{effect:function(t){var e=t.state,n={popper:{position:e.options.strategy,left:"0",top:"0",margin:"0"},arrow:{position:"absolute"},reference:{}};Object.assign(e.elements.popper.style,n.popper),e.styles=n,e.elements.arrow&&Object.assign(e.elements.arrow.style,n.arrow)}}),X={mouseover:"mouseenter",focusin:"focus",click:"click"};var Y={name:"animateFill",defaultValue:!1,fn:function(t){var e;if(null==(e=t.props.render)||!e.$$tippy)return{};var n=B(t.popper),r=n.box,o=n.content,i=t.props.animateFill?function(){var t=m();return t.className="tippy-backdrop",x([t],"hidden"),t}():null;return{onCreate:function(){i&&(r.insertBefore(i,r.firstElementChild),r.setAttribute("data-animatefill",""),r.style.overflow="hidden",t.setProps({arrow:!1,animation:"shift-away"}))},onMount:function(){if(i){var t=r.style.transitionDuration,e=Number(t.replace("ms",""));o.style.transitionDelay=Math.round(e/10)+"ms",i.style.transitionDuration=t,x([i],"visible")}},onShow:function(){i&&(i.style.transitionDuration="0ms")},onHide:function(){i&&x([i],"hidden")}}}};var q={clientX:0,clientY:0},$=[];function J(t){var e=t.clientX,n=t.clientY;q={clientX:e,clientY:n}}var G={name:"followCursor",defaultValue:!1,fn:function(t){var e=t.reference,n=E(t.props.triggerTarget||e),r=!1,o=!1,i=!0,a=t.props;function s(){return"initial"===t.props.followCursor&&t.state.isVisible}function u(){n.addEventListener("mousemove",f)}function p(){n.removeEventListener("mousemove",f)}function c(){r=!0,t.setProps({getReferenceClientRect:null}),r=!1}function f(n){var r=!n.target||e.contains(n.target),o=t.props.followCursor,i=n.clientX,a=n.clientY,s=e.getBoundingClientRect(),u=i-s.left,p=a-s.top;!r&&t.props.interactive||t.setProps({getReferenceClientRect:function(){var t=e.getBoundingClientRect(),n=i,r=a;"initial"===o&&(n=t.left+u,r=t.top+p);var s="horizontal"===o?t.top:r,c="vertical"===o?t.right:n,f="horizontal"===o?t.bottom:r,l="vertical"===o?t.left:n;return{width:c-l,height:f-s,top:s,right:c,bottom:f,left:l}}})}function l(){t.props.followCursor&&($.push({instance:t,doc:n}),function(t){t.addEventListener("mousemove",J)}(n))}function d(){0===($=$.filter((function(e){return e.instance!==t}))).filter((function(t){return t.doc===n})).length&&function(t){t.removeEventListener("mousemove",J)}(n)}return{onCreate:l,onDestroy:d,onBeforeUpdate:function(){a=t.props},onAfterUpdate:function(e,n){var i=n.followCursor;r||void 0!==i&&a.followCursor!==i&&(d(),i?(l(),!t.state.isMounted||o||s()||u()):(p(),c()))},onMount:function(){t.props.followCursor&&!o&&(i&&(f(q),i=!1),s()||u())},onTrigger:function(t,e){h(e)&&(q={clientX:e.clientX,clientY:e.clientY}),o="focus"===e.type},onHidden:function(){t.props.followCursor&&(c(),p(),i=!0)}}}};var K={name:"inlinePositioning",defaultValue:!1,fn:function(t){var e,n=t.reference;var r=-1,o=!1,i=[],a={name:"tippyInlinePositioning",enabled:!0,phase:"afterWrite",fn:function(o){var a=o.state;t.props.inlinePositioning&&(-1!==i.indexOf(a.placement)&&(i=[]),e!==a.placement&&-1===i.indexOf(a.placement)&&(i.push(a.placement),t.setProps({getReferenceClientRect:function(){return function(t){return function(t,e,n,r){if(n.length<2||null===t)return e;if(2===n.length&&r>=0&&n[0].left>n[1].right)return n[r]||e;switch(t){case"top":case"bottom":var o=n[0],i=n[n.length-1],a="top"===t,s=o.top,u=i.bottom,p=a?o.left:i.left,c=a?o.right:i.right;return{top:s,bottom:u,left:p,right:c,width:c-p,height:u-s};case"left":case"right":var f=Math.min.apply(Math,n.map((function(t){return t.left}))),l=Math.max.apply(Math,n.map((function(t){return t.right}))),d=n.filter((function(e){return"left"===t?e.left===f:e.right===l})),v=d[0].top,m=d[d.length-1].bottom;return{top:v,bottom:m,left:f,right:l,width:l-f,height:m-v};default:return e}}(l(t),n.getBoundingClientRect(),d(n.getClientRects()),r)}(a.placement)}})),e=a.placement)}};function s(){var e;o||(e=function(t,e){var n;return{popperOptions:Object.assign({},t.popperOptions,{modifiers:[].concat(((null==(n=t.popperOptions)?void 0:n.modifiers)||[]).filter((function(t){return t.name!==e.name})),[e])})}}(t.props,a),o=!0,t.setProps(e),o=!1)}return{onCreate:s,onAfterUpdate:s,onTrigger:function(e,n){if(h(n)){var o=d(t.reference.getClientRects()),i=o.find((function(t){return t.left-2<=n.clientX&&t.right+2>=n.clientX&&t.top-2<=n.clientY&&t.bottom+2>=n.clientY})),a=o.indexOf(i);r=a>-1?a:r}},onHidden:function(){r=-1}}}};var Q={name:"sticky",defaultValue:!1,fn:function(t){var e=t.reference,n=t.popper;function r(e){return!0===t.props.sticky||t.props.sticky===e}var o=null,i=null;function a(){var s=r("reference")?(t.popperInstance?t.popperInstance.state.elements.reference:e).getBoundingClientRect():null,u=r("popper")?n.getBoundingClientRect():null;(s&&Z(o,s)||u&&Z(i,u))&&t.popperInstance&&t.popperInstance.update(),o=s,i=u,t.state.isMounted&&requestAnimationFrame(a)}return{onMount:function(){t.props.sticky&&a()}}}};function Z(t,e){return!t||!e||(t.top!==e.top||t.right!==e.right||t.bottom!==e.bottom||t.left!==e.left)}return e&&function(t){var e=document.createElement("style");e.textContent=t,e.setAttribute("data-tippy-stylesheet","");var n=document.head,r=document.querySelector("head>style,head>link");r?n.insertBefore(e,r):n.appendChild(e)}('.tippy-box[data-animation=fade][data-state=hidden]{opacity:0}[data-tippy-root]{max-width:calc(100vw - 10px)}.tippy-box{position:relative;background-color:#333;color:#fff;border-radius:4px;font-size:14px;line-height:1.4;white-space:normal;outline:0;transition-property:transform,visibility,opacity}.tippy-box[data-placement^=top]>.tippy-arrow{bottom:0}.tippy-box[data-placement^=top]>.tippy-arrow:before{bottom:-7px;left:0;border-width:8px 8px 0;border-top-color:initial;transform-origin:center top}.tippy-box[data-placement^=bottom]>.tippy-arrow{top:0}.tippy-box[data-placement^=bottom]>.tippy-arrow:before{top:-7px;left:0;border-width:0 8px 8px;border-bottom-color:initial;transform-origin:center bottom}.tippy-box[data-placement^=left]>.tippy-arrow{right:0}.tippy-box[data-placement^=left]>.tippy-arrow:before{border-width:8px 0 8px 8px;border-left-color:initial;right:-7px;transform-origin:center left}.tippy-box[data-placement^=right]>.tippy-arrow{left:0}.tippy-box[data-placement^=right]>.tippy-arrow:before{left:-7px;border-width:8px 8px 8px 0;border-right-color:initial;transform-origin:center right}.tippy-box[data-inertia][data-state=visible]{transition-timing-function:cubic-bezier(.54,1.5,.38,1.11)}.tippy-arrow{width:16px;height:16px;color:#333}.tippy-arrow:before{content:"";position:absolute;border-color:transparent;border-style:solid}.tippy-content{position:relative;padding:5px 9px;z-index:1}'),F.setDefaultProps({plugins:[Y,G,K,Q],render:N}),F.createSingleton=function(t,e){var n;void 0===e&&(e={});var r,o=t,i=[],a=[],s=e.overrides,u=[],f=!1;function l(){a=o.map((function(t){return c(t.props.triggerTarget||t.reference)})).reduce((function(t,e){return t.concat(e)}),[])}function d(){i=o.map((function(t){return t.reference}))}function v(t){o.forEach((function(e){t?e.enable():e.disable()}))}function g(t){return o.map((function(e){var n=e.setProps;return e.setProps=function(o){n(o),e.reference===r&&t.setProps(o)},function(){e.setProps=n}}))}function h(t,e){var n=a.indexOf(e);if(e!==r){r=e;var u=(s||[]).concat("content").reduce((function(t,e){return t[e]=o[n].props[e],t}),{});t.setProps(Object.assign({},u,{getReferenceClientRect:"function"==typeof u.getReferenceClientRect?u.getReferenceClientRect:function(){var t;return null==(t=i[n])?void 0:t.getBoundingClientRect()}}))}}v(!1),d(),l();var b={fn:function(){return{onDestroy:function(){v(!0)},onHidden:function(){r=null},onClickOutside:function(t){t.props.showOnCreate&&!f&&(f=!0,r=null)},onShow:function(t){t.props.showOnCreate&&!f&&(f=!0,h(t,i[0]))},onTrigger:function(t,e){h(t,e.currentTarget)}}}},y=F(m(),Object.assign({},p(e,["overrides"]),{plugins:[b].concat(e.plugins||[]),triggerTarget:a,popperOptions:Object.assign({},e.popperOptions,{modifiers:[].concat((null==(n=e.popperOptions)?void 0:n.modifiers)||[],[W])})})),w=y.show;y.show=function(t){if(w(),!r&&null==t)return h(y,i[0]);if(!r||null!=t){if("number"==typeof t)return i[t]&&h(y,i[t]);if(o.indexOf(t)>=0){var e=t.reference;return h(y,e)}return i.indexOf(t)>=0?h(y,t):void 0}},y.showNext=function(){var t=i[0];if(!r)return y.show(0);var e=i.indexOf(r);y.show(i[e+1]||t)},y.showPrevious=function(){var t=i[i.length-1];if(!r)return y.show(t);var e=i.indexOf(r),n=i[e-1]||t;y.show(n)};var x=y.setProps;return y.setProps=function(t){s=t.overrides||s,x(t)},y.setInstances=function(t){v(!0),u.forEach((function(t){return t()})),o=t,v(!1),d(),l(),u=g(y),y.setProps({triggerTarget:a})},u=g(y),y},F.delegate=function(t,e){var n=[],o=[],i=!1,a=e.target,s=p(e,["target"]),u=Object.assign({},s,{trigger:"manual",touch:!1}),f=Object.assign({touch:R.touch},s,{showOnCreate:!0}),l=F(t,u);function d(t){if(t.target&&!i){var n=t.target.closest(a);if(n){var r=n.getAttribute("data-tippy-trigger")||e.trigger||R.trigger;if(!n._tippy&&!("touchstart"===t.type&&"boolean"==typeof f.touch||"touchstart"!==t.type&&r.indexOf(X[t.type])<0)){var s=F(n,f);s&&(o=o.concat(s))}}}}function v(t,e,r,o){void 0===o&&(o=!1),t.addEventListener(e,r,o),n.push({node:t,eventType:e,handler:r,options:o})}return c(l).forEach((function(t){var e=t.destroy,a=t.enable,s=t.disable;t.destroy=function(t){void 0===t&&(t=!0),t&&o.forEach((function(t){t.destroy()})),o=[],n.forEach((function(t){var e=t.node,n=t.eventType,r=t.handler,o=t.options;e.removeEventListener(n,r,o)})),n=[],e()},t.enable=function(){a(),o.forEach((function(t){return t.enable()})),i=!1},t.disable=function(){s(),o.forEach((function(t){return t.disable()})),i=!0},function(t){var e=t.reference;v(e,"touchstart",d,r),v(e,"mouseover",d),v(e,"focusin",d),v(e,"click",d)}(t)})),l},F.hideAll=function(t){var e=void 0===t?{}:t,n=e.exclude,r=e.duration;_.forEach((function(t){var e=!1;if(n&&(e=b(n)?t.reference===n:t.popper===n.popper),!e){var o=t.props.duration;t.setProps({duration:r}),t.hide(),t.state.isDestroyed||t.setProps({duration:o})}}))},F.roundArrow='<svg width="16" height="6" xmlns="http://www.w3.org/2000/svg"><path d="M0 6s1.796-.013 4.67-3.615C5.851.9 6.93.006 8 0c1.07-.006 2.148.887 3.343 2.385C14.233 6.005 16 6 16 6H0z"></svg>',F}));
//# sourceMappingURL=tippy-bundle.umd.min.js.map
//     Underscore.js 1.5.2
//     http://underscorejs.org
//     (c) 2009-2013 Jeremy Ashkenas, DocumentCloud and Investigative Reporters & Editors
//     Underscore may be freely distributed under the MIT license.

(function() {

  // Baseline setup
  // --------------

  // Establish the root object, `window` in the browser, or `exports` on the server.
  var root = this;

  // Save the previous value of the `_` variable.
  var previousUnderscore = root._;

  // Establish the object that gets returned to break out of a loop iteration.
  var breaker = {};

  // Save bytes in the minified (but not gzipped) version:
  var ArrayProto = Array.prototype, ObjProto = Object.prototype, FuncProto = Function.prototype;

  // Create quick reference variables for speed access to core prototypes.
  var
    push             = ArrayProto.push,
    slice            = ArrayProto.slice,
    concat           = ArrayProto.concat,
    toString         = ObjProto.toString,
    hasOwnProperty   = ObjProto.hasOwnProperty;

  // All **ECMAScript 5** native function implementations that we hope to use
  // are declared here.
  var
    nativeForEach      = ArrayProto.forEach,
    nativeMap          = ArrayProto.map,
    nativeReduce       = ArrayProto.reduce,
    nativeReduceRight  = ArrayProto.reduceRight,
    nativeFilter       = ArrayProto.filter,
    nativeEvery        = ArrayProto.every,
    nativeSome         = ArrayProto.some,
    nativeIndexOf      = ArrayProto.indexOf,
    nativeLastIndexOf  = ArrayProto.lastIndexOf,
    nativeIsArray      = Array.isArray,
    nativeKeys         = Object.keys,
    nativeBind         = FuncProto.bind;

  // Create a safe reference to the Underscore object for use below.
  var _ = function(obj) {
    if (obj instanceof _) return obj;
    if (!(this instanceof _)) return new _(obj);
    this._wrapped = obj;
  };

  // Export the Underscore object for **Node.js**, with
  // backwards-compatibility for the old `require()` API. If we're in
  // the browser, add `_` as a global object via a string identifier,
  // for Closure Compiler "advanced" mode.
  if (typeof exports !== 'undefined') {
    if (typeof module !== 'undefined' && module.exports) {
      exports = module.exports = _;
    }
    exports._ = _;
  } else {
    root._ = _;
  }

  // Current version.
  _.VERSION = '1.5.2';

  // Collection Functions
  // --------------------

  // The cornerstone, an `each` implementation, aka `forEach`.
  // Handles objects with the built-in `forEach`, arrays, and raw objects.
  // Delegates to **ECMAScript 5**'s native `forEach` if available.
  var each = _.each = _.forEach = function(obj, iterator, context) {
    if (obj == null) return;
    if (nativeForEach && obj.forEach === nativeForEach) {
      obj.forEach(iterator, context);
    } else if (obj.length === +obj.length) {
      for (var i = 0, length = obj.length; i < length; i++) {
        if (iterator.call(context, obj[i], i, obj) === breaker) return;
      }
    } else {
      var keys = _.keys(obj);
      for (var i = 0, length = keys.length; i < length; i++) {
        if (iterator.call(context, obj[keys[i]], keys[i], obj) === breaker) return;
      }
    }
  };

  // Return the results of applying the iterator to each element.
  // Delegates to **ECMAScript 5**'s native `map` if available.
  _.map = _.collect = function(obj, iterator, context) {
    var results = [];
    if (obj == null) return results;
    if (nativeMap && obj.map === nativeMap) return obj.map(iterator, context);
    each(obj, function(value, index, list) {
      results.push(iterator.call(context, value, index, list));
    });
    return results;
  };

  var reduceError = 'Reduce of empty array with no initial value';

  // **Reduce** builds up a single result from a list of values, aka `inject`,
  // or `foldl`. Delegates to **ECMAScript 5**'s native `reduce` if available.
  _.reduce = _.foldl = _.inject = function(obj, iterator, memo, context) {
    var initial = arguments.length > 2;
    if (obj == null) obj = [];
    if (nativeReduce && obj.reduce === nativeReduce) {
      if (context) iterator = _.bind(iterator, context);
      return initial ? obj.reduce(iterator, memo) : obj.reduce(iterator);
    }
    each(obj, function(value, index, list) {
      if (!initial) {
        memo = value;
        initial = true;
      } else {
        memo = iterator.call(context, memo, value, index, list);
      }
    });
    if (!initial) throw new TypeError(reduceError);
    return memo;
  };

  // The right-associative version of reduce, also known as `foldr`.
  // Delegates to **ECMAScript 5**'s native `reduceRight` if available.
  _.reduceRight = _.foldr = function(obj, iterator, memo, context) {
    var initial = arguments.length > 2;
    if (obj == null) obj = [];
    if (nativeReduceRight && obj.reduceRight === nativeReduceRight) {
      if (context) iterator = _.bind(iterator, context);
      return initial ? obj.reduceRight(iterator, memo) : obj.reduceRight(iterator);
    }
    var length = obj.length;
    if (length !== +length) {
      var keys = _.keys(obj);
      length = keys.length;
    }
    each(obj, function(value, index, list) {
      index = keys ? keys[--length] : --length;
      if (!initial) {
        memo = obj[index];
        initial = true;
      } else {
        memo = iterator.call(context, memo, obj[index], index, list);
      }
    });
    if (!initial) throw new TypeError(reduceError);
    return memo;
  };

  // Return the first value which passes a truth test. Aliased as `detect`.
  _.find = _.detect = function(obj, iterator, context) {
    var result;
    any(obj, function(value, index, list) {
      if (iterator.call(context, value, index, list)) {
        result = value;
        return true;
      }
    });
    return result;
  };

  // Return all the elements that pass a truth test.
  // Delegates to **ECMAScript 5**'s native `filter` if available.
  // Aliased as `select`.
  _.filter = _.select = function(obj, iterator, context) {
    var results = [];
    if (obj == null) return results;
    if (nativeFilter && obj.filter === nativeFilter) return obj.filter(iterator, context);
    each(obj, function(value, index, list) {
      if (iterator.call(context, value, index, list)) results.push(value);
    });
    return results;
  };

  // Return all the elements for which a truth test fails.
  _.reject = function(obj, iterator, context) {
    return _.filter(obj, function(value, index, list) {
      return !iterator.call(context, value, index, list);
    }, context);
  };

  // Determine whether all of the elements match a truth test.
  // Delegates to **ECMAScript 5**'s native `every` if available.
  // Aliased as `all`.
  _.every = _.all = function(obj, iterator, context) {
    iterator || (iterator = _.identity);
    var result = true;
    if (obj == null) return result;
    if (nativeEvery && obj.every === nativeEvery) return obj.every(iterator, context);
    each(obj, function(value, index, list) {
      if (!(result = result && iterator.call(context, value, index, list))) return breaker;
    });
    return !!result;
  };

  // Determine if at least one element in the object matches a truth test.
  // Delegates to **ECMAScript 5**'s native `some` if available.
  // Aliased as `any`.
  var any = _.some = _.any = function(obj, iterator, context) {
    iterator || (iterator = _.identity);
    var result = false;
    if (obj == null) return result;
    if (nativeSome && obj.some === nativeSome) return obj.some(iterator, context);
    each(obj, function(value, index, list) {
      if (result || (result = iterator.call(context, value, index, list))) return breaker;
    });
    return !!result;
  };

  // Determine if the array or object contains a given value (using `===`).
  // Aliased as `include`.
  _.contains = _.include = function(obj, target) {
    if (obj == null) return false;
    if (nativeIndexOf && obj.indexOf === nativeIndexOf) return obj.indexOf(target) != -1;
    return any(obj, function(value) {
      return value === target;
    });
  };

  // Invoke a method (with arguments) on every item in a collection.
  _.invoke = function(obj, method) {
    var args = slice.call(arguments, 2);
    var isFunc = _.isFunction(method);
    return _.map(obj, function(value) {
      return (isFunc ? method : value[method]).apply(value, args);
    });
  };

  // Convenience version of a common use case of `map`: fetching a property.
  _.pluck = function(obj, key) {
    return _.map(obj, function(value){ return value[key]; });
  };

  // Convenience version of a common use case of `filter`: selecting only objects
  // containing specific `key:value` pairs.
  _.where = function(obj, attrs, first) {
    if (_.isEmpty(attrs)) return first ? void 0 : [];
    return _[first ? 'find' : 'filter'](obj, function(value) {
      for (var key in attrs) {
        if (attrs[key] !== value[key]) return false;
      }
      return true;
    });
  };

  // Convenience version of a common use case of `find`: getting the first object
  // containing specific `key:value` pairs.
  _.findWhere = function(obj, attrs) {
    return _.where(obj, attrs, true);
  };

  // Return the maximum element or (element-based computation).
  // Can't optimize arrays of integers longer than 65,535 elements.
  // See [WebKit Bug 80797](https://bugs.webkit.org/show_bug.cgi?id=80797)
  _.max = function(obj, iterator, context) {
    if (!iterator && _.isArray(obj) && obj[0] === +obj[0] && obj.length < 65535) {
      return Math.max.apply(Math, obj);
    }
    if (!iterator && _.isEmpty(obj)) return -Infinity;
    var result = {computed : -Infinity, value: -Infinity};
    each(obj, function(value, index, list) {
      var computed = iterator ? iterator.call(context, value, index, list) : value;
      computed > result.computed && (result = {value : value, computed : computed});
    });
    return result.value;
  };

  // Return the minimum element (or element-based computation).
  _.min = function(obj, iterator, context) {
    if (!iterator && _.isArray(obj) && obj[0] === +obj[0] && obj.length < 65535) {
      return Math.min.apply(Math, obj);
    }
    if (!iterator && _.isEmpty(obj)) return Infinity;
    var result = {computed : Infinity, value: Infinity};
    each(obj, function(value, index, list) {
      var computed = iterator ? iterator.call(context, value, index, list) : value;
      computed < result.computed && (result = {value : value, computed : computed});
    });
    return result.value;
  };

  // Shuffle an array, using the modern version of the
  // [Fisher-Yates shuffle](http://en.wikipedia.org/wiki/Fisher–Yates_shuffle).
  _.shuffle = function(obj) {
    var rand;
    var index = 0;
    var shuffled = [];
    each(obj, function(value) {
      rand = _.random(index++);
      shuffled[index - 1] = shuffled[rand];
      shuffled[rand] = value;
    });
    return shuffled;
  };

  // Sample **n** random values from a collection.
  // If **n** is not specified, returns a single random element.
  // The internal `guard` argument allows it to work with `map`.
  _.sample = function(obj, n, guard) {
    if (n == null || guard) {
      if (obj.length !== +obj.length) obj = _.values(obj);
      return obj[_.random(obj.length - 1)];
    }
    return _.shuffle(obj).slice(0, Math.max(0, n));
  };

  // An internal function to generate lookup iterators.
  var lookupIterator = function(value) {
    return _.isFunction(value) ? value : function(obj){ return obj[value]; };
  };

  // Sort the object's values by a criterion produced by an iterator.
  _.sortBy = function(obj, value, context) {
    var iterator = lookupIterator(value);
    return _.pluck(_.map(obj, function(value, index, list) {
      return {
        value: value,
        index: index,
        criteria: iterator.call(context, value, index, list)
      };
    }).sort(function(left, right) {
      var a = left.criteria;
      var b = right.criteria;
      if (a !== b) {
        if (a > b || a === void 0) return 1;
        if (a < b || b === void 0) return -1;
      }
      return left.index - right.index;
    }), 'value');
  };

  // An internal function used for aggregate "group by" operations.
  var group = function(behavior) {
    return function(obj, value, context) {
      var result = {};
      var iterator = value == null ? _.identity : lookupIterator(value);
      each(obj, function(value, index) {
        var key = iterator.call(context, value, index, obj);
        behavior(result, key, value);
      });
      return result;
    };
  };

  // Groups the object's values by a criterion. Pass either a string attribute
  // to group by, or a function that returns the criterion.
  _.groupBy = group(function(result, key, value) {
    (_.has(result, key) ? result[key] : (result[key] = [])).push(value);
  });

  // Indexes the object's values by a criterion, similar to `groupBy`, but for
  // when you know that your index values will be unique.
  _.indexBy = group(function(result, key, value) {
    result[key] = value;
  });

  // Counts instances of an object that group by a certain criterion. Pass
  // either a string attribute to count by, or a function that returns the
  // criterion.
  _.countBy = group(function(result, key) {
    _.has(result, key) ? result[key]++ : result[key] = 1;
  });

  // Use a comparator function to figure out the smallest index at which
  // an object should be inserted so as to maintain order. Uses binary search.
  _.sortedIndex = function(array, obj, iterator, context) {
    iterator = iterator == null ? _.identity : lookupIterator(iterator);
    var value = iterator.call(context, obj);
    var low = 0, high = array.length;
    while (low < high) {
      var mid = (low + high) >>> 1;
      iterator.call(context, array[mid]) < value ? low = mid + 1 : high = mid;
    }
    return low;
  };

  // Safely create a real, live array from anything iterable.
  _.toArray = function(obj) {
    if (!obj) return [];
    if (_.isArray(obj)) return slice.call(obj);
    if (obj.length === +obj.length) return _.map(obj, _.identity);
    return _.values(obj);
  };

  // Return the number of elements in an object.
  _.size = function(obj) {
    if (obj == null) return 0;
    return (obj.length === +obj.length) ? obj.length : _.keys(obj).length;
  };

  // Array Functions
  // ---------------

  // Get the first element of an array. Passing **n** will return the first N
  // values in the array. Aliased as `head` and `take`. The **guard** check
  // allows it to work with `_.map`.
  _.first = _.head = _.take = function(array, n, guard) {
    if (array == null) return void 0;
    return (n == null) || guard ? array[0] : slice.call(array, 0, n);
  };

  // Returns everything but the last entry of the array. Especially useful on
  // the arguments object. Passing **n** will return all the values in
  // the array, excluding the last N. The **guard** check allows it to work with
  // `_.map`.
  _.initial = function(array, n, guard) {
    return slice.call(array, 0, array.length - ((n == null) || guard ? 1 : n));
  };

  // Get the last element of an array. Passing **n** will return the last N
  // values in the array. The **guard** check allows it to work with `_.map`.
  _.last = function(array, n, guard) {
    if (array == null) return void 0;
    if ((n == null) || guard) {
      return array[array.length - 1];
    } else {
      return slice.call(array, Math.max(array.length - n, 0));
    }
  };

  // Returns everything but the first entry of the array. Aliased as `tail` and `drop`.
  // Especially useful on the arguments object. Passing an **n** will return
  // the rest N values in the array. The **guard**
  // check allows it to work with `_.map`.
  _.rest = _.tail = _.drop = function(array, n, guard) {
    return slice.call(array, (n == null) || guard ? 1 : n);
  };

  // Trim out all falsy values from an array.
  _.compact = function(array) {
    return _.filter(array, _.identity);
  };

  // Internal implementation of a recursive `flatten` function.
  var flatten = function(input, shallow, output) {
    if (shallow && _.every(input, _.isArray)) {
      return concat.apply(output, input);
    }
    each(input, function(value) {
      if (_.isArray(value) || _.isArguments(value)) {
        shallow ? push.apply(output, value) : flatten(value, shallow, output);
      } else {
        output.push(value);
      }
    });
    return output;
  };

  // Flatten out an array, either recursively (by default), or just one level.
  _.flatten = function(array, shallow) {
    return flatten(array, shallow, []);
  };

  // Return a version of the array that does not contain the specified value(s).
  _.without = function(array) {
    return _.difference(array, slice.call(arguments, 1));
  };

  // Produce a duplicate-free version of the array. If the array has already
  // been sorted, you have the option of using a faster algorithm.
  // Aliased as `unique`.
  _.uniq = _.unique = function(array, isSorted, iterator, context) {
    if (_.isFunction(isSorted)) {
      context = iterator;
      iterator = isSorted;
      isSorted = false;
    }
    var initial = iterator ? _.map(array, iterator, context) : array;
    var results = [];
    var seen = [];
    each(initial, function(value, index) {
      if (isSorted ? (!index || seen[seen.length - 1] !== value) : !_.contains(seen, value)) {
        seen.push(value);
        results.push(array[index]);
      }
    });
    return results;
  };

  // Produce an array that contains the union: each distinct element from all of
  // the passed-in arrays.
  _.union = function() {
    return _.uniq(_.flatten(arguments, true));
  };

  // Produce an array that contains every item shared between all the
  // passed-in arrays.
  _.intersection = function(array) {
    var rest = slice.call(arguments, 1);
    return _.filter(_.uniq(array), function(item) {
      return _.every(rest, function(other) {
        return _.indexOf(other, item) >= 0;
      });
    });
  };

  // Take the difference between one array and a number of other arrays.
  // Only the elements present in just the first array will remain.
  _.difference = function(array) {
    var rest = concat.apply(ArrayProto, slice.call(arguments, 1));
    return _.filter(array, function(value){ return !_.contains(rest, value); });
  };

  // Zip together multiple lists into a single array -- elements that share
  // an index go together.
  _.zip = function() {
    var length = _.max(_.pluck(arguments, "length").concat(0));
    var results = new Array(length);
    for (var i = 0; i < length; i++) {
      results[i] = _.pluck(arguments, '' + i);
    }
    return results;
  };

  // Converts lists into objects. Pass either a single array of `[key, value]`
  // pairs, or two parallel arrays of the same length -- one of keys, and one of
  // the corresponding values.
  _.object = function(list, values) {
    if (list == null) return {};
    var result = {};
    for (var i = 0, length = list.length; i < length; i++) {
      if (values) {
        result[list[i]] = values[i];
      } else {
        result[list[i][0]] = list[i][1];
      }
    }
    return result;
  };

  // If the browser doesn't supply us with indexOf (I'm looking at you, **MSIE**),
  // we need this function. Return the position of the first occurrence of an
  // item in an array, or -1 if the item is not included in the array.
  // Delegates to **ECMAScript 5**'s native `indexOf` if available.
  // If the array is large and already in sort order, pass `true`
  // for **isSorted** to use binary search.
  _.indexOf = function(array, item, isSorted) {
    if (array == null) return -1;
    var i = 0, length = array.length;
    if (isSorted) {
      if (typeof isSorted == 'number') {
        i = (isSorted < 0 ? Math.max(0, length + isSorted) : isSorted);
      } else {
        i = _.sortedIndex(array, item);
        return array[i] === item ? i : -1;
      }
    }
    if (nativeIndexOf && array.indexOf === nativeIndexOf) return array.indexOf(item, isSorted);
    for (; i < length; i++) if (array[i] === item) return i;
    return -1;
  };

  // Delegates to **ECMAScript 5**'s native `lastIndexOf` if available.
  _.lastIndexOf = function(array, item, from) {
    if (array == null) return -1;
    var hasIndex = from != null;
    if (nativeLastIndexOf && array.lastIndexOf === nativeLastIndexOf) {
      return hasIndex ? array.lastIndexOf(item, from) : array.lastIndexOf(item);
    }
    var i = (hasIndex ? from : array.length);
    while (i--) if (array[i] === item) return i;
    return -1;
  };

  // Generate an integer Array containing an arithmetic progression. A port of
  // the native Python `range()` function. See
  // [the Python documentation](http://docs.python.org/library/functions.html#range).
  _.range = function(start, stop, step) {
    if (arguments.length <= 1) {
      stop = start || 0;
      start = 0;
    }
    step = arguments[2] || 1;

    var length = Math.max(Math.ceil((stop - start) / step), 0);
    var idx = 0;
    var range = new Array(length);

    while(idx < length) {
      range[idx++] = start;
      start += step;
    }

    return range;
  };

  // Function (ahem) Functions
  // ------------------

  // Reusable constructor function for prototype setting.
  var ctor = function(){};

  // Create a function bound to a given object (assigning `this`, and arguments,
  // optionally). Delegates to **ECMAScript 5**'s native `Function.bind` if
  // available.
  _.bind = function(func, context) {
    var args, bound;
    if (nativeBind && func.bind === nativeBind) return nativeBind.apply(func, slice.call(arguments, 1));
    if (!_.isFunction(func)) throw new TypeError;
    args = slice.call(arguments, 2);
    return bound = function() {
      if (!(this instanceof bound)) return func.apply(context, args.concat(slice.call(arguments)));
      ctor.prototype = func.prototype;
      var self = new ctor;
      ctor.prototype = null;
      var result = func.apply(self, args.concat(slice.call(arguments)));
      if (Object(result) === result) return result;
      return self;
    };
  };

  // Partially apply a function by creating a version that has had some of its
  // arguments pre-filled, without changing its dynamic `this` context.
  _.partial = function(func) {
    var args = slice.call(arguments, 1);
    return function() {
      return func.apply(this, args.concat(slice.call(arguments)));
    };
  };

  // Bind all of an object's methods to that object. Useful for ensuring that
  // all callbacks defined on an object belong to it.
  _.bindAll = function(obj) {
    var funcs = slice.call(arguments, 1);
    if (funcs.length === 0) throw new Error("bindAll must be passed function names");
    each(funcs, function(f) { obj[f] = _.bind(obj[f], obj); });
    return obj;
  };

  // Memoize an expensive function by storing its results.
  _.memoize = function(func, hasher) {
    var memo = {};
    hasher || (hasher = _.identity);
    return function() {
      var key = hasher.apply(this, arguments);
      return _.has(memo, key) ? memo[key] : (memo[key] = func.apply(this, arguments));
    };
  };

  // Delays a function for the given number of milliseconds, and then calls
  // it with the arguments supplied.
  _.delay = function(func, wait) {
    var args = slice.call(arguments, 2);
    return setTimeout(function(){ return func.apply(null, args); }, wait);
  };

  // Defers a function, scheduling it to run after the current call stack has
  // cleared.
  _.defer = function(func) {
    return _.delay.apply(_, [func, 1].concat(slice.call(arguments, 1)));
  };

  // Returns a function, that, when invoked, will only be triggered at most once
  // during a given window of time. Normally, the throttled function will run
  // as much as it can, without ever going more than once per `wait` duration;
  // but if you'd like to disable the execution on the leading edge, pass
  // `{leading: false}`. To disable execution on the trailing edge, ditto.
  _.throttle = function(func, wait, options) {
    var context, args, result;
    var timeout = null;
    var previous = 0;
    options || (options = {});
    var later = function() {
      previous = options.leading === false ? 0 : new Date;
      timeout = null;
      result = func.apply(context, args);
    };
    return function() {
      var now = new Date;
      if (!previous && options.leading === false) previous = now;
      var remaining = wait - (now - previous);
      context = this;
      args = arguments;
      if (remaining <= 0) {
        clearTimeout(timeout);
        timeout = null;
        previous = now;
        result = func.apply(context, args);
      } else if (!timeout && options.trailing !== false) {
        timeout = setTimeout(later, remaining);
      }
      return result;
    };
  };

  // Returns a function, that, as long as it continues to be invoked, will not
  // be triggered. The function will be called after it stops being called for
  // N milliseconds. If `immediate` is passed, trigger the function on the
  // leading edge, instead of the trailing.
  _.debounce = function(func, wait, immediate) {
    var timeout, args, context, timestamp, result;
    return function() {
      context = this;
      args = arguments;
      timestamp = new Date();
      var later = function() {
        var last = (new Date()) - timestamp;
        if (last < wait) {
          timeout = setTimeout(later, wait - last);
        } else {
          timeout = null;
          if (!immediate) result = func.apply(context, args);
        }
      };
      var callNow = immediate && !timeout;
      if (!timeout) {
        timeout = setTimeout(later, wait);
      }
      if (callNow) result = func.apply(context, args);
      return result;
    };
  };

  // Returns a function that will be executed at most one time, no matter how
  // often you call it. Useful for lazy initialization.
  _.once = function(func) {
    var ran = false, memo;
    return function() {
      if (ran) return memo;
      ran = true;
      memo = func.apply(this, arguments);
      func = null;
      return memo;
    };
  };

  // Returns the first function passed as an argument to the second,
  // allowing you to adjust arguments, run code before and after, and
  // conditionally execute the original function.
  _.wrap = function(func, wrapper) {
    return function() {
      var args = [func];
      push.apply(args, arguments);
      return wrapper.apply(this, args);
    };
  };

  // Returns a function that is the composition of a list of functions, each
  // consuming the return value of the function that follows.
  _.compose = function() {
    var funcs = arguments;
    return function() {
      var args = arguments;
      for (var i = funcs.length - 1; i >= 0; i--) {
        args = [funcs[i].apply(this, args)];
      }
      return args[0];
    };
  };

  // Returns a function that will only be executed after being called N times.
  _.after = function(times, func) {
    return function() {
      if (--times < 1) {
        return func.apply(this, arguments);
      }
    };
  };

  // Object Functions
  // ----------------

  // Retrieve the names of an object's properties.
  // Delegates to **ECMAScript 5**'s native `Object.keys`
  _.keys = nativeKeys || function(obj) {
    if (obj !== Object(obj)) throw new TypeError('Invalid object');
    var keys = [];
    for (var key in obj) if (_.has(obj, key)) keys.push(key);
    return keys;
  };

  // Retrieve the values of an object's properties.
  _.values = function(obj) {
    var keys = _.keys(obj);
    var length = keys.length;
    var values = new Array(length);
    for (var i = 0; i < length; i++) {
      values[i] = obj[keys[i]];
    }
    return values;
  };

  // Convert an object into a list of `[key, value]` pairs.
  _.pairs = function(obj) {
    var keys = _.keys(obj);
    var length = keys.length;
    var pairs = new Array(length);
    for (var i = 0; i < length; i++) {
      pairs[i] = [keys[i], obj[keys[i]]];
    }
    return pairs;
  };

  // Invert the keys and values of an object. The values must be serializable.
  _.invert = function(obj) {
    var result = {};
    var keys = _.keys(obj);
    for (var i = 0, length = keys.length; i < length; i++) {
      result[obj[keys[i]]] = keys[i];
    }
    return result;
  };

  // Return a sorted list of the function names available on the object.
  // Aliased as `methods`
  _.functions = _.methods = function(obj) {
    var names = [];
    for (var key in obj) {
      if (_.isFunction(obj[key])) names.push(key);
    }
    return names.sort();
  };

  // Extend a given object with all the properties in passed-in object(s).
  _.extend = function(obj) {
    each(slice.call(arguments, 1), function(source) {
      if (source) {
        for (var prop in source) {
          obj[prop] = source[prop];
        }
      }
    });
    return obj;
  };

  // Return a copy of the object only containing the whitelisted properties.
  _.pick = function(obj) {
    var copy = {};
    var keys = concat.apply(ArrayProto, slice.call(arguments, 1));
    each(keys, function(key) {
      if (key in obj) copy[key] = obj[key];
    });
    return copy;
  };

   // Return a copy of the object without the blacklisted properties.
  _.omit = function(obj) {
    var copy = {};
    var keys = concat.apply(ArrayProto, slice.call(arguments, 1));
    for (var key in obj) {
      if (!_.contains(keys, key)) copy[key] = obj[key];
    }
    return copy;
  };

  // Fill in a given object with default properties.
  _.defaults = function(obj) {
    each(slice.call(arguments, 1), function(source) {
      if (source) {
        for (var prop in source) {
          if (obj[prop] === void 0) obj[prop] = source[prop];
        }
      }
    });
    return obj;
  };

  // Create a (shallow-cloned) duplicate of an object.
  _.clone = function(obj) {
    if (!_.isObject(obj)) return obj;
    return _.isArray(obj) ? obj.slice() : _.extend({}, obj);
  };

  // Invokes interceptor with the obj, and then returns obj.
  // The primary purpose of this method is to "tap into" a method chain, in
  // order to perform operations on intermediate results within the chain.
  _.tap = function(obj, interceptor) {
    interceptor(obj);
    return obj;
  };

  // Internal recursive comparison function for `isEqual`.
  var eq = function(a, b, aStack, bStack) {
    // Identical objects are equal. `0 === -0`, but they aren't identical.
    // See the [Harmony `egal` proposal](http://wiki.ecmascript.org/doku.php?id=harmony:egal).
    if (a === b) return a !== 0 || 1 / a == 1 / b;
    // A strict comparison is necessary because `null == undefined`.
    if (a == null || b == null) return a === b;
    // Unwrap any wrapped objects.
    if (a instanceof _) a = a._wrapped;
    if (b instanceof _) b = b._wrapped;
    // Compare `[[Class]]` names.
    var className = toString.call(a);
    if (className != toString.call(b)) return false;
    switch (className) {
      // Strings, numbers, dates, and booleans are compared by value.
      case '[object String]':
        // Primitives and their corresponding object wrappers are equivalent; thus, `"5"` is
        // equivalent to `new String("5")`.
        return a == String(b);
      case '[object Number]':
        // `NaN`s are equivalent, but non-reflexive. An `egal` comparison is performed for
        // other numeric values.
        return a != +a ? b != +b : (a == 0 ? 1 / a == 1 / b : a == +b);
      case '[object Date]':
      case '[object Boolean]':
        // Coerce dates and booleans to numeric primitive values. Dates are compared by their
        // millisecond representations. Note that invalid dates with millisecond representations
        // of `NaN` are not equivalent.
        return +a == +b;
      // RegExps are compared by their source patterns and flags.
      case '[object RegExp]':
        return a.source == b.source &&
               a.global == b.global &&
               a.multiline == b.multiline &&
               a.ignoreCase == b.ignoreCase;
    }
    if (typeof a != 'object' || typeof b != 'object') return false;
    // Assume equality for cyclic structures. The algorithm for detecting cyclic
    // structures is adapted from ES 5.1 section 15.12.3, abstract operation `JO`.
    var length = aStack.length;
    while (length--) {
      // Linear search. Performance is inversely proportional to the number of
      // unique nested structures.
      if (aStack[length] == a) return bStack[length] == b;
    }
    // Objects with different constructors are not equivalent, but `Object`s
    // from different frames are.
    var aCtor = a.constructor, bCtor = b.constructor;
    if (aCtor !== bCtor && !(_.isFunction(aCtor) && (aCtor instanceof aCtor) &&
                             _.isFunction(bCtor) && (bCtor instanceof bCtor))) {
      return false;
    }
    // Add the first object to the stack of traversed objects.
    aStack.push(a);
    bStack.push(b);
    var size = 0, result = true;
    // Recursively compare objects and arrays.
    if (className == '[object Array]') {
      // Compare array lengths to determine if a deep comparison is necessary.
      size = a.length;
      result = size == b.length;
      if (result) {
        // Deep compare the contents, ignoring non-numeric properties.
        while (size--) {
          if (!(result = eq(a[size], b[size], aStack, bStack))) break;
        }
      }
    } else {
      // Deep compare objects.
      for (var key in a) {
        if (_.has(a, key)) {
          // Count the expected number of properties.
          size++;
          // Deep compare each member.
          if (!(result = _.has(b, key) && eq(a[key], b[key], aStack, bStack))) break;
        }
      }
      // Ensure that both objects contain the same number of properties.
      if (result) {
        for (key in b) {
          if (_.has(b, key) && !(size--)) break;
        }
        result = !size;
      }
    }
    // Remove the first object from the stack of traversed objects.
    aStack.pop();
    bStack.pop();
    return result;
  };

  // Perform a deep comparison to check if two objects are equal.
  _.isEqual = function(a, b) {
    return eq(a, b, [], []);
  };

  // Is a given array, string, or object empty?
  // An "empty" object has no enumerable own-properties.
  _.isEmpty = function(obj) {
    if (obj == null) return true;
    if (_.isArray(obj) || _.isString(obj)) return obj.length === 0;
    for (var key in obj) if (_.has(obj, key)) return false;
    return true;
  };

  // Is a given value a DOM element?
  _.isElement = function(obj) {
    return !!(obj && obj.nodeType === 1);
  };

  // Is a given value an array?
  // Delegates to ECMA5's native Array.isArray
  _.isArray = nativeIsArray || function(obj) {
    return toString.call(obj) == '[object Array]';
  };

  // Is a given variable an object?
  _.isObject = function(obj) {
    return obj === Object(obj);
  };

  // Add some isType methods: isArguments, isFunction, isString, isNumber, isDate, isRegExp.
  each(['Arguments', 'Function', 'String', 'Number', 'Date', 'RegExp'], function(name) {
    _['is' + name] = function(obj) {
      return toString.call(obj) == '[object ' + name + ']';
    };
  });

  // Define a fallback version of the method in browsers (ahem, IE), where
  // there isn't any inspectable "Arguments" type.
  if (!_.isArguments(arguments)) {
    _.isArguments = function(obj) {
      return !!(obj && _.has(obj, 'callee'));
    };
  }

  // Optimize `isFunction` if appropriate.
  if (typeof (/./) !== 'function') {
    _.isFunction = function(obj) {
      return typeof obj === 'function';
    };
  }

  // Is a given object a finite number?
  _.isFinite = function(obj) {
    return isFinite(obj) && !isNaN(parseFloat(obj));
  };

  // Is the given value `NaN`? (NaN is the only number which does not equal itself).
  _.isNaN = function(obj) {
    return _.isNumber(obj) && obj != +obj;
  };

  // Is a given value a boolean?
  _.isBoolean = function(obj) {
    return obj === true || obj === false || toString.call(obj) == '[object Boolean]';
  };

  // Is a given value equal to null?
  _.isNull = function(obj) {
    return obj === null;
  };

  // Is a given variable undefined?
  _.isUndefined = function(obj) {
    return obj === void 0;
  };

  // Shortcut function for checking if an object has a given property directly
  // on itself (in other words, not on a prototype).
  _.has = function(obj, key) {
    return hasOwnProperty.call(obj, key);
  };

  // Utility Functions
  // -----------------

  // Run Underscore.js in *noConflict* mode, returning the `_` variable to its
  // previous owner. Returns a reference to the Underscore object.
  _.noConflict = function() {
    root._ = previousUnderscore;
    return this;
  };

  // Keep the identity function around for default iterators.
  _.identity = function(value) {
    return value;
  };

  // Run a function **n** times.
  _.times = function(n, iterator, context) {
    var accum = Array(Math.max(0, n));
    for (var i = 0; i < n; i++) accum[i] = iterator.call(context, i);
    return accum;
  };

  // Return a random integer between min and max (inclusive).
  _.random = function(min, max) {
    if (max == null) {
      max = min;
      min = 0;
    }
    return min + Math.floor(Math.random() * (max - min + 1));
  };

  // List of HTML entities for escaping.
  var entityMap = {
    escape: {
      '&': '&amp;',
      '<': '&lt;',
      '>': '&gt;',
      '"': '&quot;',
      "'": '&#x27;'
    }
  };
  entityMap.unescape = _.invert(entityMap.escape);

  // Regexes containing the keys and values listed immediately above.
  var entityRegexes = {
    escape:   new RegExp('[' + _.keys(entityMap.escape).join('') + ']', 'g'),
    unescape: new RegExp('(' + _.keys(entityMap.unescape).join('|') + ')', 'g')
  };

  // Functions for escaping and unescaping strings to/from HTML interpolation.
  _.each(['escape', 'unescape'], function(method) {
    _[method] = function(string) {
      if (string == null) return '';
      return ('' + string).replace(entityRegexes[method], function(match) {
        return entityMap[method][match];
      });
    };
  });

  // If the value of the named `property` is a function then invoke it with the
  // `object` as context; otherwise, return it.
  _.result = function(object, property) {
    if (object == null) return void 0;
    var value = object[property];
    return _.isFunction(value) ? value.call(object) : value;
  };

  // Add your own custom functions to the Underscore object.
  _.mixin = function(obj) {
    each(_.functions(obj), function(name) {
      var func = _[name] = obj[name];
      _.prototype[name] = function() {
        var args = [this._wrapped];
        push.apply(args, arguments);
        return result.call(this, func.apply(_, args));
      };
    });
  };

  // Generate a unique integer id (unique within the entire client session).
  // Useful for temporary DOM ids.
  var idCounter = 0;
  _.uniqueId = function(prefix) {
    var id = ++idCounter + '';
    return prefix ? prefix + id : id;
  };

  // By default, Underscore uses ERB-style template delimiters, change the
  // following template settings to use alternative delimiters.
  _.templateSettings = {
    evaluate    : /<%([\s\S]+?)%>/g,
    interpolate : /<%=([\s\S]+?)%>/g,
    escape      : /<%-([\s\S]+?)%>/g
  };

  // When customizing `templateSettings`, if you don't want to define an
  // interpolation, evaluation or escaping regex, we need one that is
  // guaranteed not to match.
  var noMatch = /(.)^/;

  // Certain characters need to be escaped so that they can be put into a
  // string literal.
  var escapes = {
    "'":      "'",
    '\\':     '\\',
    '\r':     'r',
    '\n':     'n',
    '\t':     't',
    '\u2028': 'u2028',
    '\u2029': 'u2029'
  };

  var escaper = /\\|'|\r|\n|\t|\u2028|\u2029/g;

  // JavaScript micro-templating, similar to John Resig's implementation.
  // Underscore templating handles arbitrary delimiters, preserves whitespace,
  // and correctly escapes quotes within interpolated code.
  _.template = function(text, data, settings) {
    var render;
    settings = _.defaults({}, settings, _.templateSettings);

    // Combine delimiters into one regular expression via alternation.
    var matcher = new RegExp([
      (settings.escape || noMatch).source,
      (settings.interpolate || noMatch).source,
      (settings.evaluate || noMatch).source
    ].join('|') + '|$', 'g');

    // Compile the template source, escaping string literals appropriately.
    var index = 0;
    var source = "__p+='";
    text.replace(matcher, function(match, escape, interpolate, evaluate, offset) {
      source += text.slice(index, offset)
        .replace(escaper, function(match) { return '\\' + escapes[match]; });

      if (escape) {
        source += "'+\n((__t=(" + escape + "))==null?'':_.escape(__t))+\n'";
      }
      if (interpolate) {
        source += "'+\n((__t=(" + interpolate + "))==null?'':__t)+\n'";
      }
      if (evaluate) {
        source += "';\n" + evaluate + "\n__p+='";
      }
      index = offset + match.length;
      return match;
    });
    source += "';\n";

    // If a variable is not specified, place data values in local scope.
    if (!settings.variable) source = 'with(obj||{}){\n' + source + '}\n';

    source = "var __t,__p='',__j=Array.prototype.join," +
      "print=function(){__p+=__j.call(arguments,'');};\n" +
      source + "return __p;\n";

    try {
      render = new Function(settings.variable || 'obj', '_', source);
    } catch (e) {
      e.source = source;
      throw e;
    }

    if (data) return render(data, _);
    var template = function(data) {
      return render.call(this, data, _);
    };

    // Provide the compiled function source as a convenience for precompilation.
    template.source = 'function(' + (settings.variable || 'obj') + '){\n' + source + '}';

    return template;
  };

  // Add a "chain" function, which will delegate to the wrapper.
  _.chain = function(obj) {
    return _(obj).chain();
  };

  // OOP
  // ---------------
  // If Underscore is called as a function, it returns a wrapped object that
  // can be used OO-style. This wrapper holds altered versions of all the
  // underscore functions. Wrapped objects may be chained.

  // Helper function to continue chaining intermediate results.
  var result = function(obj) {
    return this._chain ? _(obj).chain() : obj;
  };

  // Add all of the Underscore functions to the wrapper object.
  _.mixin(_);

  // Add all mutator Array functions to the wrapper.
  each(['pop', 'push', 'reverse', 'shift', 'sort', 'splice', 'unshift'], function(name) {
    var method = ArrayProto[name];
    _.prototype[name] = function() {
      var obj = this._wrapped;
      method.apply(obj, arguments);
      if ((name == 'shift' || name == 'splice') && obj.length === 0) delete obj[0];
      return result.call(this, obj);
    };
  });

  // Add all accessor Array functions to the wrapper.
  each(['concat', 'join', 'slice'], function(name) {
    var method = ArrayProto[name];
    _.prototype[name] = function() {
      return result.call(this, method.apply(this._wrapped, arguments));
    };
  });

  _.extend(_.prototype, {

    // Start chaining a wrapped Underscore object.
    chain: function() {
      this._chain = true;
      return this;
    },

    // Extracts the result from a wrapped and chained object.
    value: function() {
      return this._wrapped;
    }

  });

}).call(this);

/**
 * DependencyLoader
 * 
 * @abstract
 */
window.DependencyLoader = (function() {

    /**
     * Methods (private)
     * 
     */

    /**
     * __attemptClosures
     * 
     * @access  private
     * @var     Array (default: [])
     */
    var __attemptClosures = [];

    /**
     * __attempts
     * 
     * @access  private
     * @var     Number (default: 0)
     */
    var __attempts = 0;

    /**
     * __attempt
     * 
     * @access  private
     * @param   Array dependencies
     * @param   Function callback
     * @return  Boolean
     */
    var __attempt = function(dependencies, callback) {
        ++__attempts;
        __checkForFailure(dependencies);
        if (__dependenciesAvailable(dependencies) === true) {
            callback.apply(DependencyLoader);
            return true;
        }
        return false;
    };

    /**
     * __checkForFailure
     * 
     * @throws  Error
     * @access  private
     * @param   Array dependencies
     * @return  void
     */
    var __checkForFailure = function(dependencies) {
        if (__attempts > 10000) {
            var msg = 'Could not complete an attempt: [';
            msg += dependencies.join(', ') + ']';
            throw new Error(msg);
        }
    };

    /**
     * __dependenciesAvailable
     * 
     * @access  private
     * @param   Array dependencies
     * @return  Boolean
     */
    var __dependenciesAvailable = function(dependencies) {
        var x = 0,
            l = dependencies.length;
        for (x; x < l; ++x) {
            if (window[dependencies[x]] === undefined) {
                return false;
            }
        }
        return true;
    };

    /**
     * Methods (public)
     * 
     */
    return {

        /**
         * load
         * 
         * @access  public
         * @return  void
         */
        load: function() {
            var index = 0,
                attempt;
            while (__attemptClosures.length > 0) {
                attempt = __attemptClosures.shift();
                if (attempt.apply(DependencyLoader) === false) {
                    __attemptClosures.push(attempt);
                }
            }
        },

        /**
         * push
         * 
         * @access  public
         * @param   Array dependencies
         * @param   Function callback
         * @return  void
         */
        push: function(dependencies, callback) {
            var args = [dependencies, callback],
                attempt = function() {
                    return __attempt.apply(DependencyLoader, args);
                };
            __attemptClosures.push(attempt);
        }
    };
})();

/**
 * RemoteURLOpener
 * 
 * @todo    Add dom change detection to deal with links that are generated on
 *          the fly (eg. HTML injected into the page).
 * @access  public
 * @var     Object
 */
var RemoteURLOpener = (function() {

    /**
     * Properties (private)
     * 
     */

    /**
     * __config
     * 
     * @access  private
     * @var     Object
     */
    var __config = {

        /**
         * ignoreClassNames
         * 
         * An array of class names that will result in those respective elements
         * being excluded from any event binding.
         * 
         * In english: elements with one of these class names will not have a
         * click event trigger a new tab or window.
         * 
         * @access  private
         * @var     Object
         */
        ignoreClassNames: [
            'remote-urls-ignore'
        ],

        /**
         * includeMailtoElements
         * 
         * Whether elements pointing to a mailto: flow ought to open in a new
         * tab or window.
         * 
         * @access  private
         * @var     Boolean (default: true)
         */
        includeMailtoElements: true,

        /**
         * invalidProtocols
         * 
         * Any elements that are pointing to resources, but with a protocol
         * defined in this array, will not have a click event listener bound to
         * them. This is because those resources are "special", and event
         * listeners should not get between them and the default browser/client
         * behaviour.
         * 
         * @access  private
         * @var     Array
         */
        invalidProtocols: [
            'chrome'
        ],

        /**
         * outboundClickParams
         * 
         * @access  private
         * @var     Object (default: {})
         */
        outboundClickParams: {},

        /**
         * validHostnames
         * 
         * An array of hostnames that are excluded from any event binding.
         * 
         * In english: any element on the page that has a hostname in this array
         * will not have a click event trigger a new tab or window.
         * 
         * @access  private
         * @var     Array
         */
        validHostnames: [
            window.location.host
        ]
    };

    /**
     * __string
     * 
     * @access  private
     * @var     String (default: 'RemoteURLOpener')
     */
    var __string = 'RemoteURLOpener';

    /**
     * Methods (private)
     * 
     */

    /**
     * __addClickEventListener
     * 
     * @access  private
     * @param   HTMLElement $element
     * @return  void
     */
    var __addClickEventListener = function($element) {
        var handler = __handleClickEvent;
        $element.addEventListener('click', handler);
    };

    /**
     * __elementAlreadyOpeningExternally
     * 
     * @access  private
     * @param   HTMLElement $element
     * @return  Boolean
     */
    var __elementAlreadyOpeningExternally = function($element) {
        var target = $element.getAttribute('target');
        if (target === null) {
            return false;
        }
        if (target === undefined) {
            return false;
        }
        target = target.trim().toLowerCase();
        if (target === '_blank') {
            return true;
        }
        return false;
    };

    /**
     * __getOutboundURL
     * 
     * @see     https://developer.mozilla.org/en-US/docs/Web/API/URL
     * @access  private
     * @param   HTMLElement $element
     * @return  String
     */
    var __getOutboundURL = function($element) {
        var href = $element.getAttribute('href');
        if (__isMailtoElement($element) === true) {
            return href;
        }
        var url = new URL(href);
        for (var key in __config.outboundClickParams) {
            var value = __config.outboundClickParams[key];
            url.searchParams.append(key, value);
        }
        url = url.toString();
        return url;
    };

    /**
     * __getSelector
     * 
     * @access  private
     * @return  String
     */
    var __getSelector = function() {
        var selector = 'a',
            ignoreClassNames = __config.ignoreClassNames;
        for (var className of ignoreClassNames) {
            selector = (selector) + ':not(.' + (className) + ')';
        }
        return selector;
    };

    /**
     * __handleClickEvent
     * 
     * @access  private
     * @param   Object event
     * @return  void
     */
    var __handleClickEvent = function(event) {
        event.preventDefault();
        var $element = this,
            url = __getOutboundURL($element);
        window.open(url);
    };

    /**
     * __isMailtoElement
     * 
     * @access  private
     * @param   HTMLElement $element
     * @return  void
     */
    var __isMailtoElement = function($element) {
        var href = $element.getAttribute('href');
        if (href === null) {
            return false;
        }
        if (href === undefined) {
            return false;
        }
        var pattern = /^mailto\:/i;
        if (href.match(pattern) === null) {
            return false;
        }
        return true;
    };

    /**
     * __isReservedElement
     * 
     * @see     https://i.imgur.com/Qnj3yBU.png
     * @access  private
     * @param   HTMLElement $element
     * @return  Boolean
     */
    var __isReservedElement = function($element) {
        try {
            var href = $element.getAttribute('href'),
                invalidProtocols = __config.invalidProtocols,
                url = new URL(href);
        } catch (err) {
            return false;
        }
        for (var invalidProtocol of invalidProtocols) {
            invalidProtocol = (invalidProtocol) + ':';
            if (invalidProtocol === url.protocol) {
                return true;
            }
        }
        return false;
    };

    /**
     * __remotableElement
     * 
     * @access  private
     * @param   HTMLElement $element
     * @return  Boolean
     */
    var __remotableElement = function($element) {
        if (__config.includeMailtoElements && __isMailtoElement($element) === true) {
            return true;
        }
        var hostname = $element.hostname;
        if (hostname === '') {
            return false;
        }
        if (__config.validHostnames.includes(hostname) === true) {
            return false;
        }
        if (__elementAlreadyOpeningExternally($element) === true) {
            return false;
        }
        return true;
    };

    /**
     * __remoteOpen
     * 
     * @access  private
     * @param   String url
     * @return  void
     */
    var __remoteOpen = function(url) {
        window.open(url);
    };

    /**
     * __scan
     * 
     * @access  private
     * @return  void
     */
    var __scan = function() {
        var selector = __getSelector(),
            $elements = document.querySelectorAll(selector);
        for (var $element of $elements) {
            if (__remotableElement($element) === false) {
                continue;
            }
            if (__isReservedElement($element) === true) {
                continue;
            }
            __addClickEventListener($element);
        }
    };

    /**
     * Methods (public)
     * 
     */
    return {

        /**
         * init
         * 
         * @access  public
         * @return  Boolean
         */
        init: function() {
            __scan();
            return true;
        },

        /**
         * setConfig
         * 
         * @access  public
         * @param   Object|String key
         * @param   undefined|String value
         * @return  Boolean
         */
        setConfig: function(key, value) {
            if (typeof key === 'object') {
                var config = key;
                __config = config;
                return true;
            }
            __config[key] = value;
            return true;
        },

        /**
         * setRef
         * 
         * @access  public
         * @param   String ref
         * @return  Boolean
         */
        setRef: function(ref) {
            var key = 'outboundClickParams',
                params = {};
            params.ref = ref;
            var value = params,
                response = RemoteURLOpener.setConfig(key, value);
            return response;
        }
    };
})();

/**
 * SpellChecker
 * 
 * @see     https://www.w3schools.com/tags/att_global_spellcheck.asp
 * @see     https://stackoverflow.com/questions/2705583/how-to-simulate-a-click-with-javascript
 * @access  public
 * @var     Object
 */
var SpellChecker = (function() {

    /**
     * Properties (private)
     * 
     */

    /**
     * __config
     * 
     * @access  private
     * @var     Object
     */
    var __config = {
    };

    /**
     * __string
     * 
     * @access  private
     * @var     String (default: 'SpellChecker')
     */
    var __string = 'SpellChecker';

    /**
     * Methods (private)
     * 
     */

    /**
     * __scan
     * 
     * @see     https://newbedev.com/select-text-node-using-queryselector
     * @access  private
     * @return  void
     */
    var __scan = function() {
        // var selector = __getSelector(),
        //     $elements = document.querySelectorAll(selector);
        // for (var $element of $elements) {
        //     if (__remotableElement($element) === false) {
        //         continue;
        //     }
        //     __addClickEventListener($element);
        // }
    };

    /**
     * Methods (public)
     * 
     */
    return {

        /**
         * init
         * 
         * @access  public
         * @return  Boolean
         */
        init: function() {
            __scan();
            return true;
        },

        /**
         * setConfig
         * 
         * @access  public
         * @param   Object|String key
         * @param   undefined|String value
         * @return  Boolean
         */
        setConfig: function(key, value) {
            if (typeof key === 'object') {
                var config = key;
                __config = config;
                return true;
            }
            __config[key] = value;
            return true;
        }
    };
})();

/**
 * Iconduck
 * 
 * @access  public
 * @var     Object
 */
window.Iconduck = (function() {

    /**
     * Methods (private)
     * 
     */

    /**
     * __getAdminConfig
     * 
     * @access  private
     * @return  Object
     */
    var __getAdminConfig = function() {
        var config = window.localStorage.getItem('config'),
            configCacheVersion = __getConfigCacheVersion('admin');
        config = JSON.parse(config)[configCacheVersion].admin;
        return config;
    };

    /**
     * __getConfigCacheVersion
     * 
     * @access  private
     * @param   String scope
     * @return  String
     */
    var __getConfigCacheVersion = function(scope) {
        var cacheVersion = __Iconduck.config[scope];
        return cacheVersion;
    };

    /**
     * __getPublicConfig
     * 
     * @access  private
     * @return  Object
     */
    var __getPublicConfig = function() {
        var config = window.localStorage.getItem('config'),
            configCacheVersion = __getConfigCacheVersion('public');
        config = JSON.parse(config)[configCacheVersion].public;
        return config;
    };

    /**
     * __loadAdminConfig
     * 
     * @access  private
     * @return  Boolean
     */
    var __loadAdminConfig = function() {
        var $script = document.createElement('script'),
            host = ConfigUtils.getHost(),
            cacheVersion = ConfigUtils.getPublicValue('cacheVersions', 'uiux', 'config.admin'),
            src = 'https://' + (host) + '/utils/config/admin?v=' + (cacheVersion);
        $script.src = src;
        document.querySelector('head').appendChild($script);
        return true;
    };

    /**
     * __setupAdminConfig
     * 
     * @access  private
     * @return  Boolean
     */
    var __setupAdminConfig = function() {
        var adminConfig = __getAdminConfig();
        ConfigUtils.setAdminData(adminConfig);
        return true;
    };

    /**
     * __setupLocalStorageAdminConfigCheckInterval
     * 
     * @access  private
     * @return  Boolean
     */
    var __setupLocalStorageAdminConfigCheckInterval = function() {
        var interval = setInterval(function() {
            var config = window.localStorage.getItem('config');
            if (config === null) {
                return false;
            }
            config = JSON.parse(config);
            var cacheVersion = __getConfigCacheVersion('admin');
            if (config[cacheVersion] === undefined) {
                return false;
            }
            if (config[cacheVersion].admin === undefined) {
                return false;
            }
            clearInterval(interval);
            __setupAdminConfig();
            FrameworkUtils.setupAdminComponentTemplates();
            __Iconduck.page.setupAdminCollections();
            return true;
        }, 10);
        return true;
    };

    /**
     * __setupLocalStoragePublicConfigCheckInterval
     * 
     * @access  private
     * @return  Boolean
     */
    var __setupLocalStoragePublicConfigCheckInterval = function() {
        var interval = setInterval(function() {
            var config = window.localStorage.getItem('config');
            if (config === null) {
                return false;
            }
            config = JSON.parse(config);
            var cacheVersion = __getConfigCacheVersion('public');
            if (config[cacheVersion] === undefined) {
                return false;
            }
            if (config[cacheVersion].public === undefined) {
                return false;
            }
            clearInterval(interval);
            __setupPublicConfig();
            __setupSentry();
            DependencyLoader.load();
            FrameworkUtils.init();
            __Iconduck.page.setupPublicCollections();
            return true;
        }, 10);
        return true;
    };

    /**
     * __setupPublicConfig
     * 
     * @access  private
     * @return  Boolean
     */
    var __setupPublicConfig = function() {
        var publicConfig = __getPublicConfig();
        ConfigUtils.setPublicData(publicConfig);
        return true;
    };

    /**
     * __setupSentry
     * 
     * @see     https://github.com/getsentry/sentry-react-native/issues/794#issuecomment-908189765
     * @access  private
     * @return  Boolean
     */
    var __setupSentry = function() {
        if (ConfigUtils.getPublicValue('services', 'sentry') === false) {
            return false;
        }
        if (window.Sentry === undefined) {
            return false;
        }
        var dns = ConfigUtils.getPublicValue('gateways', 'sentry', 'auth', 'dsn');
        Sentry.init({
            dsn: dns,
            integrations: [
                new Sentry.Integrations.Breadcrumbs({
                    console: false
                })
            ],
            beforeSend(event) {
                if (ConfigUtils.getRole() === 'local') {
                    __showSentryExceptionGrowlNotification(event);
                    return event;
                }
                if (ConfigUtils.getRole() === 'dev') {
                    __showSentryExceptionGrowlNotification(event);
                    return event;
                }
                if (AuthUtils.admin() === true) {
                    __showSentryExceptionGrowlNotification(event);
                    return event;
                }
                return event;
            }
        });
        return true;
    };

    /**
     * __showSentryExceptionGrowlNotification
     * 
     * @access  private
     * @param   Object event
     * @return  Boolean
     */
    var __showSentryExceptionGrowlNotification = function(event) {
        var msg = 'Exception: ' + (event.exception.values[0].value),
            timeout = 60 * 1000;
        NotificationUtils.showSimpleGrowl(msg, timeout);
        return true;
    };

    /**
     * Methods (public)
     * 
     */
    return {

        /**
         * init
         * 
         * @access  public
         * @return  void
         */
        init: function() {
            __setupLocalStoragePublicConfigCheckInterval();
        },

        /**
         * loadAdminConfig
         * 
         * @access  public
         * @return  void
         */
        loadAdminConfig: function() {
            __loadAdminConfig();
            __setupLocalStorageAdminConfigCheckInterval();
        }
    };
})();
document.addEventListener('DOMContentLoaded', Iconduck.init);
window.DependencyLoader.push(['BaseActiveRecord', 'ApplicationModel'], function() {

    /**
     * ApplicationActiveRecord
     * 
     * @extends BaseActiveRecord
     */
    window.ApplicationActiveRecord = BaseActiveRecord.extend({

        /**
         * Properties
         * 
         */

        /**
         * _figmaPlugin
         * 
         * @access  protected
         * @var     null|FigmaPluginActiveRecord
         */
        _figmaPlugin: null,

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('Application'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'ApplicationActiveRecord')
         */
        _string: 'ApplicationActiveRecord',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Object publicData
         * @return  void
         */
        init: function(publicData) {
            this._super(publicData);
            this._setupFigmaPlugin();
        },

        /**
         * _setupFigmaPlugin
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupFigmaPlugin: function() {
            var publicData = this._publicData.figmaPlugin;
            if (publicData === null) {
                return false;
            }
            if (publicData === undefined) {
                return false;
            }
            if (publicData.publicId === undefined) {
                return false;
            }
            var model = FrameworkUtils.getModel('FigmaPlugin');
            this._figmaPlugin = model.setActiveRecord(publicData);
            return true;
        },

        /**
         * figmaPlugin
         * 
         * @access  public
         * @return  Boolean
         */
        figmaPlugin: function() {
            if (this._figmaPlugin === null) {
                return false;
            }
            if (this._figmaPlugin === undefined) {
                return false;
            }
            return true;
        },

        /**
         * getFigmaPlugin
         * 
         * @access  public
         * @return  null|FigmaPluginActiveRecord
         */
        getFigmaPlugin: function() {
            var figmaPlugin = this._figmaPlugin;
            return figmaPlugin;
        },

        /**
         * getName
         * 
         * @access  public
         * @return  String
         */
        getName: function() {
            if (this.figmaPlugin() === true) {
                var name = this._figmaPlugin.getVectorSetName();
                return name;
            }
            var name = this._publicData.name;
            return name;
        },

        /**
         * reloadActiveRecords
         * 
         * @access  public
         * @return  Boolean
         */
        reloadActiveRecords: function() {
            this._setupFigmaPlugin();
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseActiveRecord', 'AssetModel'], function() {

    /**
     * AssetActiveRecord
     * 
     * @extends BaseActiveRecord
     */
    window.AssetActiveRecord = BaseActiveRecord.extend({

        /**
         * Properties
         * 
         */

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('Asset'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'AssetActiveRecord')
         */
        _string: 'AssetActiveRecord',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Object publicData
         * @return  void
         */
        init: function(publicData) {
            this._super(publicData);
        },

        /**
         * cleaned
         * 
         * @access  public
         * @return  Boolean
         */
        cleaned: function() {
            var cleaned = this._publicData.cleaned.toInt();
            cleaned = cleaned === 1;
            return cleaned;
        },

        /**
         * source
         * 
         * @access  public
         * @return  Boolean
         */
        source: function() {
            var source = this.cleaned() === false;
            return source;
        }
    });
});
window.DependencyLoader.push(['Base'], function() {

    /**
     * BaseActiveRecord
     * 
     * @fires   collection/added
     * @fires   collection/removed
     * @fires   delete/start
     * @fires   delete/complete
     * @fires   change
     * @fires   change/{columnKey}
     * @extends Base
     */
    window.BaseActiveRecord = Base.extend({

        /**
         * Properties
         * 
         */

        /**
         * _deleted
         * 
         * @access  protected
         * @var     Boolean (default: false)
         */
        _deleted: false,

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: null,

        /**
         * _publicData
         * 
         * @access  protected
         * @var     Boolean (default: false)
         */
        _publicData: false,

        /**
         * _read
         * 
         * Tracks whether the active record has been read via an XHR call. This
         * can be useful to prevent superfluous requests (when "true" data isn't
         * crucial).
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _read: null,

        /**
         * _readFields
         * 
         * @access  protected
         * @var     Array (default: [])
         */
        _readFields: [],

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'BaseActiveRecord')
         */
        _string: 'BaseActiveRecord',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Object publicData
         * @return  void
         */
        init: function(publicData) {
            this._super();
            this._publicData = publicData;
        },

        /**
         * _delete
         * 
         * @access  protected
         * @return  Promise
         */
        _delete: function() {
            var promise = this._model.delete(this).then(function(activeRecord) {
                activeRecord.triggerCustomEvent('delete/complete');
                return activeRecord;
            });
            return promise;
        },

        /**
         * _handleReadRequestResponse
         * 
         * @access  protected
         * @param   BaseActiveRecord activeRecord
         * @return  Promise
         */
        _handleReadRequestResponse: function(activeRecord) {
            this._read = true;
            return activeRecord;
        },

        /**
         * _update
         * 
         * @access  protected
         * @param   String propertyKey
         * @param   mixed value
         * @return  Promise
         */
        _update: function(propertyKey, value) {
            var data = {};
            data[propertyKey] = value;
            var promise = this._model.update(this, data);
            return promise;
        },

        /**
         * deletable
         * 
         * Returns false if the record was created over 7 days ago.
         * 
         * @access  public
         * @return  Promise
         */
        deletable: function() {
            var createdTimestamp = this._publicData.createdTimestamp,
                minimumTimestamp = DateTimeUtils.current() - 7 * 24 * 60 * 60;
            if (createdTimestamp < minimumTimestamp) {
                return false;
            }
            return true;
        },

        /**
         * delete
         * 
         * @access  public
         * @return  Promise
         */
        delete: function() {
            this._deleted = true;
            var promise = this._delete();
            this.triggerCustomEvent('delete/start');
            return promise;
        },

        /**
         * deleted
         * 
         * @access  public
         * @return  Boolean
         */
        deleted: function() {
            var deleted = this._deleted;
            return deleted;
        },

        /**
         * get
         * 
         * @access  public
         * @param   String key
         * @return  mixed
         */
        get: function(key) {
            var value = this._publicData[key];
            return value;
        },

        /**
         * getActiveRecordType
         * 
         * @access  public
         * @return  String
         */
        getActiveRecordType: function() {
            var str = this._string,
                type = str.replace(/ActiveRecord$/, '');
            return type;
        },

        /**
         * merge
         * 
         * @see     https://www.javascripttutorial.net/object/javascript-merge-objects/
         * @access  public
         * @param   Object publicData
         * @return  Boolean
         */
        merge: function(publicData) {
            var events = [];
            for (var columnKey in publicData) {
                if (columnKey === 'publicId') {
                    continue;
                }
                if (this._publicData[columnKey] === undefined) {
                    continue;
                }
                if (publicData[columnKey] === undefined) {
                    continue;
                }
                if (this._publicData[columnKey] === publicData[columnKey]) {
                    continue;
                }

                // Event tracking
                var value = publicData[columnKey],
                    event = {};
                event.name = 'change';
                event.args = [columnKey, value];
                events.push(event);

                // Event tracking
                var event = {};
                event.name = 'change/' + (columnKey);
                event.args = [value];
                events.push(event);
            }
            this._publicData = Object.assign(this._publicData, publicData);
            for (var event of events) {
                this.triggerCustomEvent(event.name, event.args);
            }
            return true;
        },

        /**
         * post
         * 
         * @access  public
         * @param   String path
         * @param   undefined|Object data (default: {})
         * @param   undefined|Object options (default: {})
         * @return  Promise
         */
        post: function(path, data, options) {
            data = data || {};
            options = options || {};
            var publicId = this._publicData.publicId,
                apiPath = this._model.getAPIPath(),
                path = (apiPath) + '/' + (publicId) + (path);
                promise = this._model.post(path, data, options);
            return promise;
        },

        /**
         * read
         * 
         * @access  public
         * @param   Boolean force (default: true)
         * @param   undefined|Array fields (default: [])
         * @return  Promise
         */
        read: function(force, fields) {
            if (force === undefined) {
                force = true;
            }
            if (fields === undefined) {
                fields = [];
            }
            if (this._read === true && force === false) {
                var promise = DataUtils.getPromise(this);
                return promise;
            }
            var fields = fields.concat(this._readFields),
                data = {};
            data.fields = fields;
            if (fields.length === 0) {
                delete data.fields;
            }
            var handler = this._handleReadRequestResponse.bind(this),
                promise = this._model.get(this, data).then(handler).then(function(activeRecord) {
                    activeRecord.reloadCollections();
                    activeRecord.reloadActiveRecords();
                    return activeRecord;
                });
            return promise;
        },

        /**
         * reloadActiveRecords
         * 
         * @access  public
         * @return  Boolean
         */
        reloadActiveRecords: function() {
            return true;
        },

        /**
         * reloadCollections
         * 
         * @access  public
         * @return  Boolean
         */
        reloadCollections: function() {
            return true;
        },

        /**
         * setColumn
         * 
         * @access  public
         * @param   String columnKey
         * @param   mixed value
         * @return  Promise
         */
        setColumn: function(columnKey, value) {
            this._publicData[columnKey] = value;
            var propertyKey = columnKey,
                promise = this._update(propertyKey, value),
                customEventName = 'change/' + (columnKey);
            this.triggerCustomEvent(customEventName, [value]);
            return promise;
        },

        /**
         * toggleColumn
         * 
         * Should (presumably) only be used against columns that are of the type
         * TINYINT.
         * 
         * @access  public
         * @param   String columnKey
         * @return  Promise
         */
        toggleColumn: function(columnKey) {
            var value = this._publicData[columnKey];
            if (value === 1) {
                var promise = this.setColumn(columnKey, 0);
                return promise;
            }
            var promise = this.setColumn(columnKey, 1);
            return promise;
        }
    });
});
window.DependencyLoader.push(['BaseActiveRecord', 'CollectionModel'], function() {

    /**
     * CollectionActiveRecord
     * 
     * @extends BaseActiveRecord
     */
    window.CollectionActiveRecord = BaseActiveRecord.extend({

        /**
         * Properties
         * 
         */

        /**
         * _collectionItems
         * 
         * @access  protected
         * @var     null|CollectionItemsCollection (default: null)
         */
        _collectionItems: null,

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('Collection'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'CollectionActiveRecord')
         */
        _string: 'CollectionActiveRecord',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Object publicData
         * @return  void
         */
        init: function(publicData) {
            this._super(publicData);
            this._setupCollectionItems();
        },

        /**
         * _setupCollectionItems
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupCollectionItems: function() {
            this._collectionItems = this._collectionItems || new CollectionItemsCollection();
            var items = this._publicData.items;
            if (items === undefined) {
                return false;
            }
            if (this._collectionItems.length() > 0) {
                return false;
            }
            var dataSet = items;
            this._collectionItems.map(dataSet);
            return true;
        },

        /**
         * add
         * 
         * @access  public
         * @param   BaseActiveRecord activeRecord
         * @return  Promise
         */
        add: function(activeRecord) {
            this._collectionItems.add(activeRecord);
            var promise = this._model.add(this, activeRecord);
            this.triggerCustomEvent('collectionItem/added');
            return promise;
        },

        /**
         * contains
         * 
         * @access  public
         * @param   BaseActiveRecord activeRecord
         * @return  Boolean
         */
        contains: function(activeRecord) {
            var contains = this._collectionItems.contains(activeRecord);
            return contains;
        },

        /**
         * delete
         * 
         * @access  public
         * @return  Promise
         */
        delete: function() {
            this.getCollectionItems().empty();
            var response = this._super();
            return response;
        },

        /**
         * deletable
         * 
         * @access  public
         * @return  Boolean
         */
        deletable: function() {
            return true;
        },

        /**
         * getCollectionItems
         * 
         * @access  public
         * @return  CollectionItemsCollection
         */
        getCollectionItems: function() {
            var collectionItems = this._collectionItems;
            return collectionItems;
        },

        /**
         * getCollectionItemsCount
         * 
         * @access  public
         * @return  Number
         */
        getCollectionItemsCount: function() {
            var length = this._collectionItems.length();
            return length;
        },

        /**
         * getCollectionItemVectorSetsCount
         * 
         * @access  public
         * @return  Number
         */
        getCollectionItemVectorSetsCount: function() {
            var length = this._collectionItems.vectorSets().length;
            return length;
        },

        /**
         * getName
         * 
         * @access  public
         * @return  String
         */
        getName: function() {
            var name = this._publicData.name;
            return name;
        },

        /**
         * getPublishedCount
         * 
         * @access  public
         * @return  Number
         */
        getPublishedCount: function() {
            var publishedCount = this._publicData.publishedCount.toInt();
            return publishedCount;
        },

        /**
         * getVectorSetPublishedCount
         * 
         * @access  public
         * @return  Number
         */
        getVectorSetPublishedCount: function() {
            var publishedVectorSetCount = this._publicData.publishedVectorSetCount.toInt();
            return publishedVectorSetCount;
        },

        /**
         * likes
         * 
         * @access  public
         * @return  Boolean
         */
        likes: function() {
            var likes = this._publicData.likes.toInt() === 1;
            return likes;
        },

        /**
         * reloadCollections
         * 
         * @access  public
         * @return  Boolean
         */
        reloadCollections: function() {
            this._setupCollectionItems();
            return true;
        },

        /**
         * remove
         * 
         * @access  public
         * @param   BaseActiveRecord activeRecord
         * @return  Promise
         */
        remove: function(activeRecord) {
            this._collectionItems.remove(activeRecord);
            var promise = this._model.remove(this, activeRecord);
            this.triggerCustomEvent('collectionItem/removed');
            return promise;
        }
    });
});
window.DependencyLoader.push(['BaseActiveRecord', 'CrashModel'], function() {

    /**
     * CrashActiveRecord
     * 
     * @extends BaseActiveRecord
     */
    window.CrashActiveRecord = BaseActiveRecord.extend({

        /**
         * Properties
         * 
         */

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('Crash'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'CrashActiveRecord')
         */
        _string: 'CrashActiveRecord',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Object publicData
         * @return  void
         */
        init: function(publicData) {
            this._super(publicData);
        }
    });
});
window.DependencyLoader.push(['BaseActiveRecord', 'DesignerModel'], function() {

    /**
     * DesignerActiveRecord
     * 
     * @extends BaseActiveRecord
     */
    window.DesignerActiveRecord = BaseActiveRecord.extend({

        /**
         * Properties
         * 
         */

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('Designer'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'DesignerActiveRecord')
         */
        _string: 'DesignerActiveRecord',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Object publicData
         * @return  void
         */
        init: function(publicData) {
            this._super(publicData);
        },

        /**
         * getName
         * 
         * @access  public
         * @return  String
         */
        getName: function() {
            var name = this._publicData.name;
            return name;
        },

        /**
         * getPath
         * 
         * @access  public
         * @return  String
         */
        getPath: function() {
            var slug = this._publicData.slug,
                path = '/designers/' + (slug);
            return path;
        }
    });
});
window.DependencyLoader.push(['BaseActiveRecord', 'FigmaPluginModel'], function() {

    /**
     * FigmaPluginActiveRecord
     * 
     * @extends BaseActiveRecord
     */
    window.FigmaPluginActiveRecord = BaseActiveRecord.extend({

        /**
         * Properties
         * 
         */

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('FigmaPlugin'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'FigmaPluginActiveRecord')
         */
        _string: 'FigmaPluginActiveRecord',

        /**
         * _vectorSet
         * 
         * @access  protected
         * @var     null|VectorSetActiveRecord
         */
        _vectorSet: null,

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Object publicData
         * @return  void
         */
        init: function(publicData) {
            this._super(publicData);
            this._setupVectorSet();
        },

        /**
         * _global
         * 
         * @access  protected
         * @return  Boolean
         */
        _global: function() {
            var vectorSetId = this._publicData.vectorSetId.toInt(),
                response = vectorSetId === 0;
            return response;
        },

        /**
         * _setupVectorSet
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupVectorSet: function() {
            var publicData = this._publicData.vectorSet;
            if (publicData === null) {
                return false;
            }
            var model = FrameworkUtils.getModel('VectorSet');
            this._vectorSet = model.setActiveRecord(publicData);
            return true;
        },

        /**
         * getVectorSetName
         * 
         * @access  public
         * @return  String
         */
        getVectorSetName: function() {
            if (this._global() === true) {
                var name = '(global)';
                return name;
            }
            var vectorSet = this._vectorSet,
                name = vectorSet.getName();
            return name;
        }
    });
});
window.DependencyLoader.push(['BaseActiveRecord', 'FingerprintModel'], function() {

    /**
     * FingerprintActiveRecord
     * 
     * @extends BaseActiveRecord
     */
    window.FingerprintActiveRecord = BaseActiveRecord.extend({

        /**
         * Properties
         * 
         */

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('Fingerprint'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'FingerprintActiveRecord')
         */
        _string: 'FingerprintActiveRecord',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Object publicData
         * @return  void
         */
        init: function(publicData) {
            this._super(publicData);
        }
    });
});
window.DependencyLoader.push(['BaseActiveRecord', 'LicenseModel'], function() {

    /**
     * LicenseActiveRecord
     * 
     * @extends BaseActiveRecord
     */
    window.LicenseActiveRecord = BaseActiveRecord.extend({

        /**
         * Properties
         * 
         */

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('License'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'LicenseActiveRecord')
         */
        _string: 'LicenseActiveRecord',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Object publicData
         * @return  void
         */
        init: function(publicData) {
            this._super(publicData);
        },

        /**
         * getShortName
         * 
         * @access  public
         * @return  String
         */
        getShortName: function() {
            var shortName = this._publicData.shortName;
            return shortName;
        },

        /**
         * getLongName
         * 
         * @access  public
         * @return  String
         */
        getLongName: function() {
            var longName = this._publicData.longName;
            return longName;
        }
    });
});
window.DependencyLoader.push(['BaseActiveRecord', 'RedirectModel'], function() {

    /**
     * RedirectActiveRecord
     * 
     * @extends BaseActiveRecord
     */
    window.RedirectActiveRecord = BaseActiveRecord.extend({

        /**
         * Properties
         * 
         */

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('Redirect'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'RedirectActiveRecord')
         */
        _string: 'RedirectActiveRecord',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Object publicData
         * @return  void
         */
        init: function(publicData) {
            this._super(publicData);
        }
    });
});
window.DependencyLoader.push(['BaseActiveRecord', 'SubsetModel'], function() {

    /**
     * SubsetActiveRecord
     * 
     * @extends BaseActiveRecord
     */
    window.SubsetActiveRecord = BaseActiveRecord.extend({

        /**
         * Properties
         * 
         */

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('Subset'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'SubsetActiveRecord')
         */
        _string: 'SubsetActiveRecord',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Object publicData
         * @return  void
         */
        init: function(publicData) {
            this._super(publicData);
        },

        /**
         * category
         * 
         * @access  public
         * @return  Boolean
         */
        category: function() {
            var category = this._publicData.group === 'category';
            return category;
        },

        /**
         * color
         * 
         * @access  public
         * @return  Boolean
         */
        color: function() {
            var color = this._publicData.group === 'color';
            return color;
        },

        /**
         * deletable
         * 
         * @access  public
         * @return  Boolean
         */
        deletable: function() {
            var publishedCount = this._publicData.publishedCount;
            if (publishedCount > 0) {
                return false;
            }
            return true;
        },

        /**
         * getLabel
         * 
         * @access  public
         * @return  String
         */
        getLabel: function() {
            var label = this._publicData.label;
            return label;
        },

        /**
         * global
         * 
         * @access  public
         * @return  Boolean
         */
        global: function() {
            var globalVar = this._publicData.global.toInt() === 1;
            return globalVar;
        },

        /**
         * style
         * 
         * @access  public
         * @return  Boolean
         */
        style: function() {
            var style = this._publicData.group === 'style';
            return style;
        },

        /**
         * type
         * 
         * @access  public
         * @return  Boolean
         */
        type: function() {
            var type = this._publicData.group === 'type';
            return type;
        }
    });
});
window.DependencyLoader.push(['BaseActiveRecord', 'UpgradeModel'], function() {

    /**
     * UpgradeActiveRecord
     * 
     * @extends BaseActiveRecord
     */
    window.UpgradeActiveRecord = BaseActiveRecord.extend({

        /**
         * Properties
         * 
         */

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('Upgrade'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'UpgradeActiveRecord')
         */
        _string: 'UpgradeActiveRecord',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Object publicData
         * @return  void
         */
        init: function(publicData) {
            this._super(publicData);
        }
    });
});
window.DependencyLoader.push(['BaseActiveRecord', 'UserModel'], function() {

    /**
     * UserActiveRecord
     * 
     * @extends BaseActiveRecord
     */
    window.UserActiveRecord = BaseActiveRecord.extend({

        /**
         * Properties
         * 
         */

        /**
         * _collections
         * 
         * @access  protected
         * @var     null|CollectionsCollection (default: null)
         */
        _collections: null,

        /**
         * _likes
         * 
         * @access  protected
         * @var     null|CollectionActiveRecord (default: null)
         */
        _likes: null,

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('User'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'UserActiveRecord')
         */
        _string: 'UserActiveRecord',

        /**
         * _upgrade
         * 
         * @access  protected
         * @var     null|UpgradActiveRecord (default: null)
         */
        _upgrade: null,

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Object publicData
         * @return  void
         */
        init: function(publicData) {
            this._super(publicData);
            this._setupCollections();
            this._setupLikes();
            this._setupUpgrade();
        },

        /**
         * _setupCollections
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupCollections: function() {
            this._collections = this._collections || new CollectionsCollection();
            var dataSet = this._publicData.collections || [];
            this._collections.map(dataSet);
            return true;
        },

        /**
         * _setupLikes
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupLikes: function() {
            var collections = this._collections.all();
            for (var collection of collections) {
                if (collection.likes() === true) {
                    this._likes = collection;
                    return true;
                }
            }
            return false;
        },

        /**
         * _setupUpgrade
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupUpgrade: function() {
            var publicData = this._publicData.upgrade;
            if (publicData === null) {
                return false;
            }
            var publicData = this._publicData.upgrade;
            if (publicData === undefined) {
                return false;
            }
            var publicId = publicData.publicId,
                name = 'Upgrade',
                upgrade = FrameworkUtils.setActiveRecord(publicId, name, publicData);
            this._upgrade = upgrade;
            return false;
        },

        /**
         * admin
         * 
         * @access  public
         * @return  Boolean
         */
        admin: function() {
            var admin = this.get('admin');
            if (admin === undefined) {
                return false;
            }
            admin = admin.toInt();
            admin = admin === 1;
            return admin;
        },

        /**
         * collected
         * 
         * @access  public
         * @param   BaseActiveRecord activeRecord
         * @return  Boolean
         */
        collected: function(activeRecord) {
            var collections = this._collections.created();
            for (var collection of collections) {
                if (collection.getCollectionItems().contains(activeRecord) === true) {
                    return true;
                }
            }
            return false;
        },

        /**
         * getCollections
         * 
         * @access  public
         * @return  CollectionsCollection
         */
        getCollections: function() {
            var collections = this._collections;
            return collections;
        },

        /**
         * getLikes
         * 
         * @access  public
         * @return  CollectionActiveRecord
         */
        getLikes: function() {
            var likes = this._likes;
            return likes;
        },

        /**
         * liked
         * 
         * @access  public
         * @param   VectorActiveRecord|VectorSetActiveRecord activeRecord
         * @return  Boolean
         */
        liked: function(activeRecord) {
            var likes = this._likes,
                liked = likes.contains(activeRecord);
            return liked;
        },

        /**
         * logout
         * 
         * @access  public
         * @return  Promise
         */
        logout: function() {
            var promise = this._model.logout();
            return promise;
        },

        /**
         * upgraded
         * 
         * @access  public
         * @return  Boolean
         */
        upgraded: function() {
            if (this.admin() === true) {
                return true;
            }
            var upgrade = this._upgrade;
            if (upgrade === null) {
                return false;
            }
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseActiveRecord', 'UserEmailTemplateModel'], function() {

    /**
     * UserEmailTemplateActiveRecord
     * 
     * @extends BaseActiveRecord
     */
    window.UserEmailTemplateActiveRecord = BaseActiveRecord.extend({

        /**
         * Properties
         * 
         */

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('UserEmailTemplate'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'UserEmailTemplateActiveRecord')
         */
        _string: 'UserEmailTemplateActiveRecord',

        /**
         * _vectorSet
         * 
         * @access  protected
         * @var     null|VectorSetActiveRecord
         */
        _vectorSet: null,

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Object publicData
         * @return  void
         */
        init: function(publicData) {
            this._super(publicData);
            this._setupVectorSet();
        },

        /**
         * _setupVectorSet
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupVectorSet: function() {
            var publicData = this._publicData.vectorSet;
            if (publicData === null) {
                return false;
            }
            if (publicData === undefined) {
                return false;
            }
            var model = FrameworkUtils.getModel('VectorSet');
            this._vectorSet = model.setActiveRecord(publicData);
            return true;
        },

        /**
         * deletable
         * 
         * @access  public
         * @return  Boolean
         */
        deletable: function() {
            var templateKey = this._publicData.templateKey;
            if (templateKey === 'users.campaigns.custom' || templateKey === 'users.campaigns.wrapper' || templateKey === 'users.vectorSets.added') {
                if (this.sending() === true) {
                    return false;
                }
                if (this.sent() === true) {
                    return false;
                }
                return true;
            }
            return false;
        },

        /**
         * getVectorSetPublicId
         * 
         * @access  public
         * @return  null|String
         */
        getVectorSetPublicId: function() {
            var publicData = this._publicData.vectorSet;
            if (publicData === null) {
                return null;
            }
            var vectorSetPublicId = publicData.publicId;
            return vectorSetPublicId;
        },

        /**
         * sending
         * 
         * @access  public
         * @return  Boolean
         */
        sending: function() {
            var sending = this._publicData.sending.toInt();
            sending = sending === 1;
            return sending;
        },

        /**
         * sent
         * 
         * @access  public
         * @return  Boolean
         */
        sent: function() {
            var sent = this._publicData.sent.toInt();
            sent = sent === 1;
            return sent;
        }
    });
});
window.DependencyLoader.push(['BaseActiveRecord', 'VectorModel'], function() {

    /**
     * VectorActiveRecord
     * 
     * @fires   preloaded
     * @fires   preloading
     * @fires   preview
     * @extends BaseActiveRecord
     */
    window.VectorActiveRecord = BaseActiveRecord.extend({

        /**
         * Properties
         * 
         */

        /**
         * _assets
         * 
         * @access  protected
         * @var     null|AssetsCollection (default: null)
         */
        _assets: null,

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('Vector'),

        /**
         * _preloaded
         * 
         * @access  protected
         * @var     Boolean (default: false)
         */
        _preloaded: false,

        /**
         * _preloading
         * 
         * @access  protected
         * @var     Boolean (default: false)
         */
        _preloading: false,

        /**
         * _promises
         * 
         * @access  protected
         * @var     Object (default: {})
         */
        _promises: {},

        /**
         * _readFields
         * 
         * @access  protected
         * @var     Array (default: ['similar', 'tags'])
         */
        // _readFields: ['similar', 'tags'],
        _readFields: ['vectorSetSubsetVectors'],

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'VectorActiveRecord')
         */
        _string: 'VectorActiveRecord',

        /**
         * _vectorSet
         * 
         * @access  protected
         * @var     null|VectorSetActiveRecord
         */
        _vectorSet: null,

        /**
         * _vectorSetSubsetVectors
         * 
         * @access  protected
         * @var     null|VectorSetSubsetVectorsCollection (default: null)
         */
        _vectorSetSubsetVectors: null,

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Object publicData
         * @return  void
         */
        init: function(publicData) {
            this._super(publicData);
            this._setupAssets();
            this._setupVectorSet();
            this._setupVectorSetSubsetVectors();
        },

        /**
         * _bitmapsExported
         * 
         * @access  protected
         * @return  Boolean
         */
        // _bitmapsExported: function() {
        //     var bitmapsExported = this._data.bitmapsExported.toInt();
        //     bitmapsExported = bitmapsExported === 1;
        //     return bitmapsExported;
        // },

        /**
         * _getApproximatedDimensions
         * 
         * @access  protected
         * @param   Number size
         * @return  Object
         */
        _getApproximatedDimensions: function(size) {
            var dimensions = {},
                asset = this.getBitmapAsset(2048),
                width = asset.get('width'),
                height = asset.get('height'),
                // asset = this._vectorData.assets[0],
                assetRatio = width / height;
            if (assetRatio >= 1) {
                var ratio = width / size;
                dimensions.width = width / ratio;
                dimensions.width = Math.ceil(dimensions.width);
                dimensions.height = height / ratio;
                dimensions.height = Math.ceil(dimensions.height);
                return dimensions;
            }
            var ratio = height / size;
            dimensions.width = width / ratio;
            dimensions.width = Math.ceil(dimensions.width);
            dimensions.height = height / ratio;
            dimensions.height = Math.ceil(dimensions.height);
            return dimensions;
        },

        /**
         * _getDownloadPNGPath
         * 
         * @access  protected
         * @param   Number size
         * @return  String
         */
        _getDownloadPNGPath: function(size) {
            var publicId = this._publicData.publicId,
                path = '/api/v2/vectors/' + (publicId) + '/media/png/' + (size) + '/download';
            return path;
        },

        /**
         * _getDownloadSVGPath
         * 
         * @access  protected
         * @return  String
         */
        _getDownloadSVGPath: function() {
            var publicId = this._publicData.publicId,
                path = '/vectors/' + (publicId) + '/media/svg/download';
            return path;
        },

        /**
         * _getDownloadZIPPath
         * 
         * @access  protected
         * @return  String
         */
        _getDownloadZIPPath: function() {
            var publicId = this._publicData.publicId,
                path = '/vectors/' + (publicId) + '/download';
            return path;
        },

        /**
         * _getLicense
         * 
         * @access  protected
         * @return  LicenseActiveRecord
         */
        _getLicense: function() {
            var vectorSet = this._vectorSet,
                license = vectorSet.getLicense();
            return license;
        },

        /**
         * _preparePNG
         * 
         * @access  protected
         * @param   Number size
         * @return  Promise
         */
        _preparePNG: function(size) {
            var publicId = this._publicData.publicId,
                path = '/vectors/' + (publicId) + '/media/png/prepare',
                data = {};
            data.size = size;
            var promise = RequestUtils.post(path, data);
            return promise;
        },

        /**
         * _setupAssets
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupAssets: function() {
            this._assets = this._assets || new AssetsCollection();
            var assets = this._publicData.assets;
            if (assets === undefined) {
                return false;
            }
            if (this._assets.length() > 0) {
                return false;
            }
            var dataSet = assets;
            this._assets.map(dataSet);
            return true;
        },

        /**
         * _setupVectorSet
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupVectorSet: function() {
            var publicData = this._publicData.vectorSet;
            if (publicData === undefined) {
                return false;
            }
            var model = FrameworkUtils.getModel('VectorSet');
            this._vectorSet = this._vectorSet || model.setActiveRecord(publicData);
            return true;
        },

        /**
         * _setupVectorSetSubsetVectors
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupVectorSetSubsetVectors: function() {
            this._vectorSetSubsetVectors = this._vectorSetSubsetVectors || new VectorSetSubsetVectorsCollection();
            var vectorSetSubsetVectors = this._publicData.vectorSetSubsetVectors;
            if (vectorSetSubsetVectors === null) {
                return false;
            }
            if (vectorSetSubsetVectors === undefined) {
                return false;
            }
            if (this._vectorSetSubsetVectors.length() > 0) {
                return false;
            }
            var dataSet = vectorSetSubsetVectors;
            this._vectorSetSubsetVectors.map(dataSet);
            return true;
        },

        /**
         * _validDownloadAttempt
         * 
         * @access  protected
         * @return  Boolean
         */
        _validDownloadAttempt: function() {
            var downloadCount = AuthUtils.getDownloadCount(),
                maxDownloadCount = AuthUtils.getMaxDownloadCount(),
                validDownloadAttempt = downloadCount < maxDownloadCount;
            return validDownloadAttempt;
        },

        /**
         * download
         * 
         * @access  public
         * @param   String type
         * @param   null|Number size
         * @return  Boolean
         */
        download: function(type, size) {
            if (this._validDownloadAttempt() === false) {
                if (AuthUtils.getUser() === null) {
                    ModalUtils.showAuthPrompt('maxDownloadCountExceeded');
                    return false;
                }
                ModalUtils.showUpsell('maxDownloadCount');
                AdminUtils.log('upsell:maxDownloadCount');
                return false;
            }
            if (type === 'png' && size.toInt() === 4096) {
                ModalUtils.showBusy('Preparing download...');
                this._preparePNG(size).then(function(response) {
                    ModalUtils.hideBusy();
                    var basename = response.data.basename,
                        url = response.data.url,
                        path = '/utils/download';
                    path += '?url=' + encodeURIComponent(url);
                    path += '&basename=' + encodeURIComponent(basename);
                    ModalUtils.showDownload(path);
                });
                return false;
            }
            if (type === 'png') {
                var path = this._getDownloadPNGPath(size);
            }
            if (type === 'svg') {
                var path = this._getDownloadSVGPath();
            }
            if (type === 'zip') {
                var path = this._getDownloadZIPPath();
            }
            WindowUtils.smartDownload(path);
            __Iconduck.page.autoShowMailingListModal() || __Iconduck.page.autoShowPromotionModal()
            return true;
        },

        /**
         * exportBitmaps
         * 
         * @access  public
         * @return  Promise
         */
        // exportBitmaps: function() {
        //     if (this._bitmapsExported() === true) {
        //         var promise = DataUtils.getPromise(this);
        //         return promise;
        //     }
        //     var promise = this._model.exportBitmaps(this);
        //     return promise;
        // },

        /**
         * getAssetDimensionsLabel
         * 
         * @access  public
         * @param   Number size
         * @return  String
         */
        getAssetDimensionsLabel: function(size) {
            var dimensions = this._getApproximatedDimensions(size),
                label = (dimensions.width) + 'x' + (dimensions.height);
            return label;
        },

        /**
         * getBitmapAsset
         * 
         * @access  public
         * @param   Number size
         * @param   Boolean useSourceAsset (default: false)
         * @return  null|AssetActiveRecord
         */
        getBitmapAsset: function(size, useSourceAsset) {
            if (useSourceAsset === undefined) {
                useSourceAsset = false;
            }
            var assets = this._assets.all();
            for (var asset of assets) {
                if (asset.get('bitmap').toInt() === 0) {
                    continue;
                }
                if (asset.get('size').toInt() !== size) {
                    continue;
                }
                if (useSourceAsset === true && asset.source() === true) {
                    return asset;
                }
                if (this.useCleanBitmaps() === true && asset.cleaned() === true) {
                    return asset;
                }
                if (this.useCleanBitmaps() === false && asset.cleaned() === false) {
                    return asset;
                }
            }
            return null;
        },

        /**
         * getFilesizeLabel
         * 
         * @link    https://stackoverflow.com/questions/15900485/correct-way-to-convert-size-in-bytes-to-kb-mb-gb-in-javascript
         * @access  public
         * @return  String
         */
        getFilesizeLabel: function() {
            var filesize = this._publicData.filesize,
                decimals = 2;
            if (filesize === 0) {
                var str = '0 bytes';
                return str;
            }
            var k = 1024,
                dm = decimals < 0 ? 0 : decimals,
                sizes = ['bytes', 'kb', 'mb', 'gb', 'tb', 'pb', 'eb', 'zb', 'yb'],
                i = Math.floor(Math.log(filesize) / Math.log(k)),
                str = parseFloat((filesize / Math.pow(k, i)).toFixed(dm)) + ' ' + sizes[i];
            return str;
        },

        /**
         * getLicenseName
         * 
         * @access  public
         * @return  String
         */
        getLicenseName: function() {
            var license = this._getLicense();
                name = license.getLongName();
            return name;
        },

        /**
         * getName
         * 
         * @access  public
         * @return  String
         */
        getName: function() {
            var name = this._publicData.name;
            return name;
        },

        /**
         * getPageTitle
         * 
         * @access  public
         * @return  String
         */
        getPageTitle: function() {
            var name = this.getName(),
                type = this.getType(),
                type = DataUtils.ucfirst(type),
                title = '"' + (name) + '" ' + (type) + ' - Download for free – Iconduck';
            return title;
        },

        /**
         * getPath
         * 
         * @access  public
         * @return  String
         */
        getPath: function() {
            var path = this._publicData.path;
            return path;
        },

        /**
         * getPNGURL
         * 
         * @access  public
         * @param   Number size
         * @param   Boolean useSourceAsset (default: false)
         * @return  String
         */
        getPNGURL: function(size, useSourceAsset) {
            if (useSourceAsset === undefined) {
                useSourceAsset = false;
            }
            var bitmapAsset = this.getBitmapAsset(size, useSourceAsset),
                url = bitmapAsset.get('url');
            // if (bitmapAsset.get('publicId') === 'asstjj1o556m') {
            //     url = url + 's';
            // }
            return url;
        },

        /**
         * getStylePropertyClasses
         * 
         * @access  public
         * @return  Array
         */
        getStylePropertyClasses: function() {
            var classes = [];
            classes.push('vector');
            if (AuthUtils.admin() === true) {
                classes.push('broken-' + this._publicData.broken);
            }
            classes.push('color-' + this._publicData.color);
            classes.push('displayShowContrast-' + this._publicData.displayShowContrast);
            if (AuthUtils.admin() === true) {
                classes.push('flagged-' + this._publicData.flagged);
            }
            classes.push('solid-' + this._publicData.solid);
            return classes;
        },

        /**
         * getTags
         * 
         * @access  public
         * @return  Array
         */
        getTags: function() {
            var tags = this._publicData.tags;
            return tags;
        },

        /**
         * getType
         * 
         * @access  public
         * @return  String
         */
        getType: function() {
            if (this._publicData.emoji === 1) {
                var type = 'emoji';
                return type;
            }
            if (this._publicData.illustration === 1) {
                var type = 'illustration';
                return type;
            }
            var type = 'icon';
            return type;
        },

        /**
         * getUIAltValue
         * 
         * @access  protected
         * @return  String
         */
        getUIAltValue: function() {
            var name = this._publicData.name,
                type = this.getType(),
                value = (name) + ' ' + (type),
                value = DataUtils.escapeString(value);
            return value;
        },

        /**
         * getURL
         * 
         * @access  public
         * @return  String
         */
        getURL: function() {
            var url = this._publicData.url;
            return url;
        },

        /**
         * getVectorSetName
         * 
         * @access  public
         * @return  String
         */
        getVectorSetName: function() {
            var vectorSet = this._vectorSet,
                name = vectorSet.getName();
            return name;
        },

        /**
         * getVectorSetPath
         * 
         * @access  public
         * @return  String
         */
        getVectorSetPath: function() {
            var vectorSet = this._vectorSet,
                path = vectorSet.getPath();
            return path;
        },

        /**
         * getVectorSetSubsetVectors
         * 
         * @access  public
         * @return  null|VectorSetSubsetVectorsCollection
         */
        getVectorSetSubsetVectors: function() {
            var vectorSetSubsetVectors = this._vectorSetSubsetVectors;
            return vectorSetSubsetVectors;
        },

        /**
         * like
         * 
         * @access  public
         * @return  Promise
         */
        like: function() {
            var likes = AuthUtils.getUser().getLikes(),
                promise = likes.add(this);
            return promise;
        },

        /**
         * unlike
         * 
         * @access  public
         * @return  Promise
         */
        unlike: function() {
            var likes = AuthUtils.getUser().getLikes(),
                promise = likes.remove(this);
            return promise;
        },

        /**
         * preload
         * 
         * @todo    Add preloading of zoom image (1024)
         *          See: https://i.imgur.com/i1Ns3U1.jpg
         * @access  public
         * @return  Promise
         */
        preload: function() {
            if (this._preloaded === true) {
                var promise = DataUtils.getPromise(this);
                return promise;
            }
            if (this._preloading === true) {
                var promise = this._promises.preload;
                return promise;
            }
            this._preloading = true;
            var promise = this._promises.preload = this.read().then(function(activeRecord) {
                return activeRecord;//.exportBitmaps();
            }).then(function(activeRecord) {
                var url = activeRecord.getPNGURL(512);
                return RequestUtils.loadImage(url).then(function(image) {
                    activeRecord.setPreloading(false);
                    activeRecord.setPreloaded(true);
                    return activeRecord;
                }).catch(function() {
                    activeRecord.setPreloading(false);
                    activeRecord.setPreloaded(true);
                    return activeRecord;
                });
            });
            return promise;
        },

        /**
         * preloaded
         * 
         * @access  public
         * @return  Boolean
         */
        preloaded: function() {
            var preloaded = this._preloaded;
            return preloaded;
        },

        /**
         * preloading
         * 
         * @access  public
         * @return  Boolean
         */
        preloading: function() {
            var preloading = this._preloading;
            return preloading;
        },

        /**
         * reloadActiveRecords
         * 
         * @access  public
         * @return  Boolean
         */
        reloadActiveRecords: function() {
            this._setupVectorSet();
            return true;
        },

        /**
         * reloadCollections
         * 
         * @access  public
         * @return  Boolean
         */
        reloadCollections: function() {
            this._setupAssets();
            this._setupVectorSetSubsetVectors();
            return true;
        },

        /**
         * setPreloaded
         * 
         * @access  public
         * @param   Boolean value
         * @return  Boolean
         */
        setPreloaded: function(value) {
            this._preloaded = value;
            this.triggerCustomEvent('preloaded');
            return true;
        },

        /**
         * setPreloading
         * 
         * @access  public
         * @param   Boolean value
         * @return  Boolean
         */
        setPreloading: function(value) {
            this._preloading = value;
            this.triggerCustomEvent('preloading');
            return true;
        },

        /**
         * showNewBadge
         * 
         * @access  public
         * @param   VectorGroupBlockComponentView vectorGroupBlock
         * @return  Boolean
         */
        showNewBadge: function(vectorGroupBlock) {
            if (this._publicData.showNewBadge === false) {
                return false;
            }
            var vectorSet = vectorGroupBlock.getAttribute('vector-set').toInt();
            if (vectorSet === 1) {
                return false;
            }
            var collection = vectorGroupBlock.getAttribute('collection').toInt();
            if (collection === 1) {
                return false;
            }
            return true;
        },

        /**
         * showPreviewModal
         * 
         * @access  public
         * @return  void
         */
        showPreviewModal: function() {
            var vectorsCollection = this._getVectorGroupVectorsCollection(),
                handler = ModalUtils.showPreview.bind(ModalUtils, vector, vectorsCollection);
            ModalUtils.showBusy();
            vector.preload().then(function() {
                ModalUtils.closeVisible();
            }).then(handler);
        },

        /**
         * trackPushState
         * 
         * @access  public
         * @param   String path
         * @return  Boolean
         */
        trackPushState: function(path) {
            // path = (path) + '?preview';
            var type = 'PreviewModalComponentView',
                title = '',
                data = {};
            data.publicId = this._publicData.publicId;
            var response = StateUtils.pushState(path, type, title, data);
            return response;
        },

        /**
         * useCleanBitmaps
         * 
         * @access  public
         * @return  Boolean
         */
        useCleanBitmaps: function() {
            var useCleanBitmaps = this._publicData.useCleanBitmaps.toInt();
            useCleanBitmaps = useCleanBitmaps === 1;
            return useCleanBitmaps;
        }
    });
});
window.DependencyLoader.push(['BaseActiveRecord', 'VectorSetModel'], function() {

    /**
     * VectorSetActiveRecord
     * 
     * @extends BaseActiveRecord
     */
    window.VectorSetActiveRecord = BaseActiveRecord.extend({

        /**
         * Properties
         * 
         */

        /**
         * _vectorSetDesigners
         * 
         * @access  protected
         * @var     null|VectorSetDesignersCollection (default: null)
         */
        _vectorSetDesigners: null,

        /**
         * _license
         * 
         * @access  protected
         * @var     null|LicenseActiveRecord
         */
        _license: null,

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('VectorSet'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'VectorSetActiveRecord')
         */
        _string: 'VectorSetActiveRecord',

        /**
         * _vectorSetSubsets
         * 
         * @access  protected
         * @var     null|VectorSetSubsetsCollection (default: null)
         */
        _vectorSetSubsets: null,

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Object publicData
         * @return  void
         */
        init: function(publicData) {
            this._super(publicData);
            this._setupLicense();
            this._setupVectorSetDesigners();
            this._setupVectorSetSubsets();
        },

        /**
         * _setupLicense
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupLicense: function() {
            var publicData = this._publicData.license;
            if (publicData === undefined) {
                return false;
            }
            var model = FrameworkUtils.getModel('License');
            this._license = this._license || model.setActiveRecord(publicData);
            return true;
        },

        /**
         * _setupVectorSetDesigners
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupVectorSetDesigners: function() {
            this._vectorSetDesigners = this._vectorSetDesigners || new VectorSetDesignersCollection();
            var vectorSetDesigners = this._publicData.vectorSetDesigners;
            if (vectorSetDesigners === undefined) {
                return false;
            }
            if (this._vectorSetDesigners.length() > 0) {
                return false;
            }
            var dataSet = vectorSetDesigners;
            this._vectorSetDesigners.map(dataSet);
            return true;
        },

        /**
         * _setupVectorSetSubsets
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupVectorSetSubsets: function() {
            this._vectorSetSubsets = this._vectorSetSubsets || new VectorSetSubsetsCollection();
            var vectorSetSubsets = this._publicData.vectorSetSubsets;
            if (vectorSetSubsets === undefined) {
                return false;
            }
            if (this._vectorSetSubsets.length() > 0) {
                return false;
            }
            var dataSet = vectorSetSubsets;
            this._vectorSetSubsets.map(dataSet);
            return true;
        },

        /**
         * deletable
         * 
         * @access  public
         * @return  Boolean
         */
        deletable: function() {
            if (this._super() === false) {
                return false;
            }
            var publishedVectorCount = this._publicData.publishedVectorCount;
            if (publishedVectorCount > 0) {
                return false;
            }
            return true;
        },

        /**
         * getLicense
         * 
         * @access  public
         * @return  LicenseActiveRecord
         */
        getLicense: function() {
            var license = this._license;
            return license;
        },

        /**
         * getName
         * 
         * @access  public
         * @return  String
         */
        getName: function() {
            var name = this._publicData.name;
            return name;
        },

        /**
         * getPath
         * 
         * @access  public
         * @return  String
         */
        getPath: function() {
            var slug = this._publicData.slug,
                path = '/sets/' + (slug);
            return path;
        },

        /**
         * getTags
         * 
         * @access  public
         * @return  Array
         */
        getTags: function() {
            var tags = this._publicData.tags;
            return tags;
        },

        /**
         * getVectorSetDesigners
         * 
         * @access  public
         * @return  VectorSetDesignersCollection
         */
        getVectorSetDesigners: function() {
            var vectorSetDesigners = this._vectorSetDesigners;
            return vectorSetDesigners;
        },

        /**
         * getVectorSetSubsets
         * 
         * @access  public
         * @return  VectorSetSubsetsCollection
         */
        getVectorSetSubsets: function() {
            var vectorSetSubsets = this._vectorSetSubsets;
            return vectorSetSubsets;
        },

        /**
         * like
         * 
         * @access  public
         * @return  Promise
         */
        like: function() {
            var likes = AuthUtils.getUser().getLikes(),
                promise = likes.add(this);
            return promise;
        },

        /**
         * reloadActiveRecords
         * 
         * @access  public
         * @return  Boolean
         */
        reloadActiveRecords: function() {
            this._setupLicense();
            return true;
        },

        /**
         * reloadCollections
         * 
         * @access  public
         * @return  Boolean
         */
        reloadCollections: function() {
            this._setupVectorSetDesigners()
            this._setupVectorSetSubsets();;
            return true;
        },

        /**
         * unlike
         * 
         * @access  public
         * @return  Promise
         */
        unlike: function() {
            var likes = AuthUtils.getUser().getLikes(),
                promise = likes.remove(this);
            return promise;
        }
    });
});
window.DependencyLoader.push(['BaseActiveRecord', 'VectorSetDesignerModel'], function() {

    /**
     * VectorSetDesignerActiveRecord
     * 
     * @extends BaseActiveRecord
     */
    window.VectorSetDesignerActiveRecord = BaseActiveRecord.extend({

        /**
         * Properties
         * 
         */

        /**
         * _designer
         * 
         * @access  protected
         * @var     null|DesignerActiveRecord
         */
        _designer: null,

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('VectorSetDesigner'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'VectorSetDesignerActiveRecord')
         */
        _string: 'VectorSetDesignerActiveRecord',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Object publicData
         * @return  void
         */
        init: function(publicData) {
            this._super(publicData);
            this._setupDesigner();
        },

        /**
         * _setupDesigner
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupDesigner: function() {
            var publicData = this._publicData.designer;
            if (publicData === undefined) {
                return false;
            }
            var model = FrameworkUtils.getModel('Designer');
            this._designer = this._designer || model.setActiveRecord(publicData);
            return true;
        },

        /**
         * getDesigner
         * 
         * @access  public
         * @return  DesignerActiveRecord
         */
        getDesigner: function() {
            var designer = this._designer;
            return designer;
        },

        /**
         * getPath
         * 
         * @access  public
         * @return  String
         */
        getPath: function() {
            var designer = this.getDesigner(),
                path = designer.getPath();
            return path;
        },

        /**
         * getVectorSet
         * 
         * @access  public
         * @return  VectorSetActiveRecord
         */
        getVectorSet: function() {
            var vectorSetPublicId = this._publicData.vectorSet.publicId,
                vectorSet = FrameworkUtils.getActiveRecord(vectorSetPublicId);
            return vectorSet;
        },

        /**
         * reloadActiveRecords
         * 
         * @access  public
         * @return  Boolean
         */
        reloadActiveRecords: function() {
            this._setupDesigner();
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseActiveRecord', 'VectorSetSubsetModel'], function() {

    /**
     * VectorSetSubsetActiveRecord
     * 
     * @extends BaseActiveRecord
     */
    window.VectorSetSubsetActiveRecord = BaseActiveRecord.extend({

        /**
         * Properties
         * 
         */

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('VectorSetSubset'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'VectorSetSubsetActiveRecord')
         */
        _string: 'VectorSetSubsetActiveRecord',

        /**
         * _subset
         * 
         * @access  protected
         * @var     null|SubsetActiveRecord (default: null)
         */
        _subset: null,

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Object publicData
         * @return  void
         */
        init: function(publicData) {
            this._super(publicData);
            this._setupSubset();
        },

        /**
         * _setupSubset
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupSubset: function() {
            var publicData = this._publicData.subset;
            if (publicData === undefined) {
                return false;
            }
            var model = FrameworkUtils.getModel('Subset');
            this._subset = this._subset || model.setActiveRecord(publicData);
            return true;
        },

        /**
         * category
         * 
         * @access  public
         * @return  Boolean
         */
        category: function() {
            var category = this.getSubset().category() === true;
            return category;
        },

        /**
         * color
         * 
         * @access  public
         * @return  Boolean
         */
        color: function() {
            var color = this.getSubset().color() === true;
            return color;
        },

        /**
         * getDescription
         * 
         * @access  public
         * @return  String
         */
        getDescription: function() {
            var description = this.getSubset().get('description');
            return description;
        },

        /**
         * getPath
         * 
         * @access  public
         * @return  String
         */
        getPath: function() {
            var path = this.getVectorSet().getPath(),
                subset = this.getSubset(),
                slug = subset.get('slug');
            if (subset.category() === true) {
                path = (path) + '/categories/' + (slug);
                return path;
            }
            if (subset.color() === true) {
                path = (path) + '/styles/' + (slug);
                return path;
            }
            if (subset.style() === true) {
                path = (path) + '/styles/' + (slug);
                return path;
            }
            path = (path) + '/' + (slug);
            return path;
        },

        /**
         * getSubset
         * 
         * @access  public
         * @return  SubsetActiveRecord
         */
        getSubset: function() {
            var subset = this._subset;
            return subset;
        },

        /**
         * getVectorSet
         * 
         * @access  public
         * @return  VectorSetActiveRecord
         */
        getVectorSet: function() {
            var vectorSetPublicId = this._publicData.vectorSet.publicId,
                vectorSet = FrameworkUtils.getActiveRecord(vectorSetPublicId);
            return vectorSet;
        },

        /**
         * global
         * 
         * @access  public
         * @return  Boolean
         */
        global: function() {
            var global = this.getSubset().global();
            return global;
        },

        /**
         * list
         * 
         * @access  public
         * @return  Boolean
         */
        list: function() {
            var list = this._publicData.list.toInt() === 1;
            return list;
        },

        /**
         * reloadActiveRecords
         * 
         * @access  public
         * @return  Boolean
         */
        reloadActiveRecords: function() {
            this._setupSubset();
            return true;
        },

        /**
         * style
         * 
         * @access  public
         * @return  Boolean
         */
        style: function() {
            var style = this.getSubset().style() === true;
            return style;
        },

        /**
         * type
         * 
         * @access  public
         * @return  Boolean
         */
        type: function() {
            var type = this.getSubset().type() === true;
            return type;
        },
    });
});
window.DependencyLoader.push(['BaseActiveRecord', 'VectorSetSubsetVectorModel'], function() {

    /**
     * VectorSetSubsetVectorActiveRecord
     * 
     * @extends BaseActiveRecord
     */
    window.VectorSetSubsetVectorActiveRecord = BaseActiveRecord.extend({

        /**
         * Properties
         * 
         */

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('VectorSetSubsetVector'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'VectorSetSubsetVectorActiveRecord')
         */
        _string: 'VectorSetSubsetVectorActiveRecord',

        /**
         * _vectorSetSubset
         * 
         * @access  protected
         * @var     null|VectorSetSubsetActiveRecord (default: null)
         */
        _vectorSetSubset: null,

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Object publicData
         * @return  void
         */
        init: function(publicData) {
            this._super(publicData);
            this._setupVectorSetSubset();
        },

        /**
         * _setupVectorSetSubset
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupVectorSetSubset: function() {
            var publicData = this._publicData.vectorSetSubset;
            if (publicData === undefined) {
                return false;
            }
            var model = FrameworkUtils.getModel('VectorSetSubset');
            this._vectorSetSubset = this._vectorSetSubset || model.setActiveRecord(publicData);
            return true;
        },

        /**
         * getLabel
         * 
         * @access  public
         * @return  String
         */
        getLabel: function() {
            var label = this._vectorSetSubset.getSubset().getLabel();
            return label;
        },

        /**
         * getPath
         * 
         * @access  public
         * @return  String
         */
        getPath: function() {
            var path = this._vectorSetSubset.getPath();
            return path;
        },

        /**
         * getSubset
         * 
         * @access  public
         * @return  SubsetActiveRecord
         */
        getSubset: function() {
            var subset = this._vectorSetSubset.getSubset();
            return subset;
        },

        /**
         * getVectorSetSubset
         * 
         * @access  public
         * @return  VectorSetSubsetActiveRecord
         */
        getVectorSetSubset: function() {
            var vectorSetSubset = this._vectorSetSubset;
            return vectorSetSubset;
        },

        /**
         * reloadActiveRecords
         * 
         * @access  public
         * @return  Boolean
         */
        reloadActiveRecords: function() {
            this._setupVectorSetSubset();
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseActiveRecord', 'VendorModel'], function() {

    /**
     * VendorActiveRecord
     * 
     * @extends BaseActiveRecord
     */
    window.VendorActiveRecord = BaseActiveRecord.extend({

        /**
         * Properties
         * 
         */

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('Vendor'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'VendorActiveRecord')
         */
        _string: 'VendorActiveRecord',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Object publicData
         * @return  void
         */
        init: function(publicData) {
            this._super(publicData);
        },

        /**
         * deletable
         * 
         * @access  public
         * @return  Boolean
         */
        deletable: function() {
            return false;
        }
    });
});

/**
 * UppyClientWrapper
 * 
 * @see     https://uppy.io/docs/dashboard/#openModal
 * @see     https://uppy.io/docs/uppy/#uppy-close
 * @extends Class
 */
window.UppyClientWrapper = Class.extend({

    /**
     * Properties
     * 
     */

    /**
     * _fallbackOptions
     * 
     * @access  protected
     * @var     Object
     */
    _fallbackOptions: {
        allowedFileTypes: ['*/*'],
        maxFileSize: 10 * 1024 * 1024,
        maxNumberOfFiles: 10,
        steps: {
            ':original': {
                'robot': '/upload/handle'
            }
        },
        waitForEncoding: false
    },

    /**
     * Methods
     * 
     */

    /**
     * init
     * 
     * @access  public
     * @return  void
     */
    init: function() {
    },

    /**
     * _addCompleteListener
     * 
     * @access  protected
     * @param   Uppy.Core uppyCore
     * @param   Function callback
     * @return  void
     */
    _addCompleteListener: function(uppyCore, callback) {
        uppyCore.on('complete', function(bundle) {
            var results = bundle.transloadit[0].results['action:deliver'] || [];
            callback.apply(callback, [results]);
            setTimeout(function() {
                uppyCore.getPlugin('Dashboard').closeModal();
            }, 750);
        });
    },

    /**
     * _addDropboxSource
     * 
     * @access  protected
     * @param   Uppy.Core uppyCore
     * @param   Object options
     * @return  Boolean
     */
    _addDropboxSource: function(uppyCore, options) {
        if (options.sources.includes('dropbox') === false) {
            return false;
        }
        var sourceOptions = this._getSourceOptions();
        uppyCore.use(Uppy.Dropbox, sourceOptions);
        return true;
    },

    /**
     * _addFacebookSource
     * 
     * @access  protected
     * @param   Uppy.Core uppyCore
     * @param   Object options
     * @return  Boolean
     */
    _addFacebookSource: function(uppyCore, options) {
        if (options.sources.includes('facebook') === false) {
            return false;
        }
        var sourceOptions = this._getSourceOptions();
        uppyCore.use(Uppy.Facebook, sourceOptions);
        return true;
    },

    /**
     * _addGoogleDriveSource
     * 
     * @access  protected
     * @param   Uppy.Core uppyCore
     * @param   Object options
     * @return  Boolean
     */
    _addGoogleDriveSource: function(uppyCore, options) {
        if (options.sources.includes('googleDrive') === false) {
            return false;
        }
        var sourceOptions = this._getSourceOptions();
        uppyCore.use(Uppy.GoogleDrive, sourceOptions);
        return true;
    },

    /**
     * _addInstagramSource
     * 
     * @access  protected
     * @param   Uppy.Core uppyCore
     * @param   Object options
     * @return  Boolean
     */
    _addInstagramSource: function(uppyCore, options) {
        if (options.sources.includes('instagram') === false) {
            return false;
        }
        var sourceOptions = this._getSourceOptions();
        uppyCore.use(Uppy.Instagram, sourceOptions);
        return true;
    },

    /**
     * _addOneDriveSource
     * 
     * @access  protected
     * @param   Uppy.Core uppyCore
     * @param   Object options
     * @return  Boolean
     */
    _addOneDriveSource: function(uppyCore, options) {
        if (options.sources.includes('oneDrive') === false) {
            return false;
        }
        var sourceOptions = this._getSourceOptions();
        uppyCore.use(Uppy.OneDrive, sourceOptions);
        return true;
    },

    /**
     * _addSources
     * 
     * @access  protected
     * @param   Uppy.Core uppyCore
     * @param   Object options
     * @return  void
     */
    _addSources: function(uppyCore, options) {
        this._addURLSource(uppyCore, options);
        this._addFacebookSource(uppyCore, options);
        this._addInstagramSource(uppyCore, options);
        this._addWebcamSource(uppyCore, options);
        this._addGoogleDriveSource(uppyCore, options);
        this._addDropboxSource(uppyCore, options);
        this._addOneDriveSource(uppyCore, options);
    },

    /**
     * _addUploadListener
     * 
     * @access  protected
     * @param   Uppy.Core uppyCore
     * @return  void
     */
    _addUploadListener: function(uppyCore) {
        var handler = this._handleUploadEvent.bind(uppyCore);
        uppyCore.on('upload', handler);
    },

    /**
     * _addURLSource
     * 
     * @access  protected
     * @param   Uppy.Core uppyCore
     * @param   Object options
     * @return  Boolean
     */
    _addURLSource: function(uppyCore, options) {
        if (options.sources.includes('url') === false) {
            return false;
        }
        var sourceOptions = this._getSourceOptions();
        uppyCore.use(Uppy.Url, sourceOptions);
        return true;
    },

    /**
     * _addWebcamSource
     * 
     * @access  protected
     * @return  Boolean
     */
    _addWebcamSource: function(uppyCore, options) {
        if (options.sources.includes('webcam') === false) {
            return false;
        }
        var webcamSourceOptions = this._getWebcamSourceOptions();
        uppyCore.use(Uppy.Webcam, webcamSourceOptions);
        return true;
    },

    /**
     * _getAllowedFileTypes
     * 
     * @access  protected
     * @param   Object options
     * @return  Array
     */
    _getAllowedFileTypes: function(options) {
        var allowedFileTypes = options.allowedFileTypes || this._fallbackOptions.allowedFileTypes;
        return allowedFileTypes;
    },

    /**
     * _getDashboardLocale
     * 
     * @access  protected
     * @return  Object
     */
    _getDashboardLocale: function() {
        var locale = {
            strings: {
                dropPasteImport: 'Import images from:'
            }
        };
        return locale;
    },

    /**
     * _getDashboardOptions
     * 
     * @link    https://uppy.io/docs/dashboard/
     * @see     https://github.com/transloadit/uppy/issues/1239
     * @access  protected
     * @return  Object
     */
    _getDashboardOptions: function() {
        var options = {
            animateOpenClose: false,
            browserBackButtonClose: false,
            closeModalOnClickOutside: true,
            height: 470,
            hideCancelButton: true,
            hidePauseResumeButton: true,
            inline: false,
            locale: this._getDashboardLocale(),
            proudlyDisplayPoweredByUppy: false,
            showLinkToFileUploadResult: false,
            showProgressDetails: true
        };
        return options;
    },

    /**
     * _getMaxFileSize
     * 
     * @access  protected
     * @param   Object options
     * @return  Number
     */
    _getMaxFileSize: function(options) {
        var maxFileSize = options.maxFileSize || this._fallbackOptions.maxFileSize;
        return maxFileSize;
    },

    /**
     * _getMaxNumberOfFiles
     * 
     * @access  protected
     * @param   Object options
     * @return  Number
     */
    _getMaxNumberOfFiles: function(options) {
        var maxNumberOfFiles = options.maxNumberOfFiles || this._fallbackOptions.maxNumberOfFiles;
        return maxNumberOfFiles;
    },

    /**
     * _getRestrictions
     * 
     * @access  protected
     * @param   Object options
     * @return  Object
     */
    _getRestrictions: function(options) {
        var allowedFileTypes = this._getAllowedFileTypes(options),
            maxFileSize = this._getMaxFileSize(options),
            maxNumberOfFiles = this._getMaxNumberOfFiles(options),
            restrictions = {
                allowedFileTypes: allowedFileTypes,
                maxFileSize: maxFileSize,
                maxNumberOfFiles: maxNumberOfFiles
            };
        return restrictions;
    },

    /**
     * _getSourceOptions
     * 
     * @access  protected
     * @return  Object
     */
    _getSourceOptions: function() {
        var options = {
            target: Uppy.Dashboard,
            // browserBackButtonClose: false,
            companionUrl: Uppy.Transloadit.COMPANION,
            companionAllowedHosts: /\.transloadit\.com$/
        };
        return options;
    },

    /**
     * _getTransloaditKey
     * 
     * @access  protected
     * @return  String
     */
    _getTransloaditKey: function() {
        // var key = Config.getGateway('transloadit').auth.key;
        var key = ConfigUtils.getAdminValue().gateways.transloadit.key;
        return key;
    },

    /**
     * _getTransloaditParams
     * 
     * @access  protected
     * @param   Object options
     * @return  Object
     */
    _getTransloaditParams: function(options) {
        var key = this._getTransloaditKey(),
            auth = {
                key: key
            },
            params = {},
            steps = this._getTransloaditSteps(options);
        params.auth = auth;
        params.steps = steps;
        return params;
    },

    /**
     * _getTransloaditSteps
     * 
     * @access  protected
     * @param   Object options
     * @return  Object
     */
    _getTransloaditSteps: function(options) {
        var steps = options.steps || this._fallbackOptions.steps;
        return steps;
    },

    /**
     * _getUppyCoreOptions
     * 
     * @access  protected
     * @param   Object options
     * @return  Object
     */
    _getUppyCoreOptions: function(options) {
        var restrictions = this._getRestrictions(options),
            options = {
                autoProceed: false,
                restrictions: restrictions
            };
        return options;
    },

    /**
     * _getWebcamSourceOptions
     * 
     * @access  protected
     * @return  Object
     */
    _getWebcamSourceOptions: function() {
        var modes = ['picture'],
            options = {
                target: Uppy.Dashboard,
                countdown: 3,
                modes: modes
            };
        return options;
    },

    /**
     * _handleUploadEvent
     * 
     * @access  protected
     * @return  void
     */
    _handleUploadEvent: function() {
    },

    /**
     * _setupDashboard
     * 
     * @see     https://github.com/transloadit/uppy/issues/2180
     * @access  protected
     * @param   Uppy.Core uppyCore
     * @return  void
     */
    _setupDashboard: function(uppyCore) {
        var options = this._getDashboardOptions();
        uppyCore.use(Uppy.Dashboard, options);
    },

    /**
     * _setupTransloadit
     * 
     * @link    https://uppy.io/docs/transloadit/
     * @access  protected
     * @param   Uppy.Core uppyCore
     * @param   Object options
     * @return  void
     */
    _setupTransloadit: function(uppyCore, options) {
        var params = this._getTransloaditParams(options),
            waitForEncoding = options.waitForEncoding || this._fallbackOptions.waitForEncoding,
            options = {
                params: params,
                waitForEncoding: waitForEncoding
            };
        uppyCore.use(Uppy.Transloadit, options);
    },

    /**
     * _setupUppyCore
     * 
     * @access  protected
     * @param   Object options
     * @return  Uppy.Core
     */
    _setupUppyCore: function(options) {
        var uppyCoreOptions = this._getUppyCoreOptions(options),
            uppyCore = Uppy.Core(uppyCoreOptions);
        return uppyCore;
    },

    /**
     * getClient
     * 
     * @access  public
     * @param   Object options
     * @return  null|Uppy.Core
     */
    getClient: function(options) {
        var uppyCore = this._setupUppyCore(options);
        this._setupTransloadit(uppyCore, options);
        this._setupDashboard(uppyCore);
        this._addSources(uppyCore, options);
        this._addCompleteListener(uppyCore, options.callback);
        this._addUploadListener(uppyCore);
        return uppyCore;
    },
});
window.DependencyLoader.push(['DatabaseTableCollection', 'ApplicationModel'], function() {

    /**
     * ApplicationsCollection
     * 
     * @extends DatabaseTableCollection
     */
    window.ApplicationsCollection = DatabaseTableCollection.extend({

        /**
         * Properties
         * 
         */

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('Application'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'ApplicationsCollection')
         */
        _string: 'ApplicationsCollection',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Array dataSet
         * @return  void
         */
        init: function(dataSet) {
            this._super(dataSet);
        }
    });
});
window.DependencyLoader.push(['DatabaseTableCollection', 'AssetModel'], function() {

    /**
     * AssetsCollection
     * 
     * @extends DatabaseTableCollection
     */
    window.AssetsCollection = DatabaseTableCollection.extend({

        /**
         * Properties
         * 
         */

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('Asset'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'AssetsCollection')
         */
        _string: 'AssetsCollection',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Array dataSet
         * @return  void
         */
        init: function(dataSet) {
            this._super(dataSet);
        }
    });
});
window.DependencyLoader.push(['Base'], function() {

    /**
     * BaseCollection
     * 
     * @fires   add
     * @fires   remove
     * @fires   empty
     * @extends Base
     */
    window.BaseCollection = Base.extend({

        /**
         * Properties
         * 
         */

        /**
         * _activeRecords
         * 
         * Overrides the parent property (which is an object), since colletions
         * will only ever store active records as an array.
         * 
         * @access  protected
         * @var     Array (default: [])
         */
        _activeRecords: [],

        /**
         * _more
         * 
         * @access  protected
         * @var     Booleanb (default: true)
         */
        _more: true,

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'BaseCollection')
         */
        _string: 'BaseCollection',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   undefined|Array dataSet (defaut: [])
         * @return  void
         */
        init: function(dataSet) {
            dataSet = dataSet || [];
            this._super();
            this._activeRecords = [];
            this.map(dataSet);
        },

        /**
         * add
         * 
         * @access  public
         * @param   BaseActiveRecord activeRecord
         * @return  Boolean
         */
        add: function(activeRecord) {
            this._activeRecords.push(activeRecord);
            var args = [activeRecord];
            this.triggerCustomEvent('add', args);
            var handler = this.remove.bind(this, activeRecord);
            activeRecord.addCustomEventListenerOnce('delete/start', handler);
            activeRecord.triggerCustomEvent('collection/added');
            return true;
        },

        /**
         * all
         * 
         * @access  public
         * @return  Array
         */
        all: function() {
            var activeRecords = this._activeRecords;
            return activeRecords;
        },

        /**
         * contains
         * 
         * @access  public
         * @param   BaseActiveRecord activeRecord
         * @return  Boolean
         */
        contains: function(activeRecord) {
            var contains = this._activeRecords.includes(activeRecord);
            return contains;
        },

        /**
         * count
         * 
         * @access  public
         * @return  Number
         */
        count: function() {
            var count = this.length();
            return count;
        },

        /**
         * filter
         * 
         * @access  public
         * @param   Function fn
         * @return  null|BaseActiveRecord
         */
        filter: function(fn) {
            var filtered = [];
            for (var activeRecord of this._activeRecords) {
                if (fn(activeRecord) === true) {
                    filtered.push(activeRecord);
                }
            }
            return filtered;
        },

        /**
         * find
         * 
         * @access  public
         * @param   String property
         * @param   mixed value
         * @return  null|BaseActiveRecord
         */
        find: function(property, value) {
            var fn = function(activeRecord) {
                    return activeRecord.get(property) === value;
                },
                filtered = this.filter(fn);
            if (filtered.length === 1) {
                return filtered[0];
            }
            return null;
        },

        /**
         * first
         * 
         * @access  public
         * @return  null|BaseActiveRecord
         */
        first: function() {
            var activeRecord = this._activeRecords[0];
            if (activeRecord === undefined) {
                return null;
            }
            return activeRecord;
        },

        /**
         * last
         * 
         * @access  public
         * @return  null|BaseActiveRecord
         */
        last: function() {
            var length = this._activeRecords.length,
                index = length - 1,
                activeRecord = this._activeRecords[index];
            if (activeRecord === undefined) {
                return null;
            }
            return activeRecord;
        },

        /**
         * length
         * 
         * @access  public
         * @return  Number
         */
        length: function() {
            var length = this._activeRecords.length;
            return length;
        },

        /**
         * more
         * 
         * @access  public
         * @return  Boolean
         */
        more: function() {
            var more = this._more;
            return more;
        },

        /**
         * next
         * 
         * @throws  Error
         * @access  public
         * @param   BaseActiveRecord current
         * @return  Promise
         */
        next: function(current) {
            if (this.contains(current) === false) {
                var msg = 'Could not find $current in active records';
                throw new Error(msg);
            }
            var next = null;
            for (var index in this._activeRecords) {
                index = index.toInt();
                var activeRecord = this._activeRecords[index];
                if (activeRecord === current) {
                    var next = this._activeRecords[index + 1];
                    if (next === undefined) {
                        next = null;
                    }
                    break;
                }
            }
            var promise = DataUtils.getPromise(next);
            return promise;
        },

        /**
         * previous
         * 
         * @throws  Error
         * @access  public
         * @param   BaseActiveRecord current
         * @return  Promise
         */
        previous: function(current) {
            if (this.contains(current) === false) {
                var msg = 'Could not find $current in active records';
                throw new Error(msg);
            }
            var previous = null;
            for (var index in this._activeRecords) {
                index = index.toInt();
                var activeRecord = this._activeRecords[index];
                if (activeRecord === current) {
                    var previous = this._activeRecords[index - 1];
                    if (previous === undefined) {
                        previous = null;
                    }
                    break;
                }
            }
            var promise = DataUtils.getPromise(previous);
            return promise;
        },

        /**
         * empty
         * 
         * @access  public
         * @return  Boolean
         */
        empty: function() {
            for (var activeRecord of this._activeRecords) {
                this.remove(activeRecord);
            }
            this.triggerCustomEvent('empty');
            return true;
        },

        /**
         * remove
         * 
         * @access  public
         * @param   BaseActiveRecord targetActiveRecord
         * @return  Boolean
         */
        remove: function(targetActiveRecord) {
            for (var index in this._activeRecords) {
                index = index.toInt();
                var activeRecord = this._activeRecords[index];
                if (activeRecord === targetActiveRecord) {
                    this._activeRecords.splice(index, 1);
                    var args = [targetActiveRecord];
                    this.triggerCustomEvent('remove', args);
                    activeRecord.triggerCustomEvent('collection/removed');
                    return true;
                }
            }
            return true;
        },

        /**
         * setMore
         * 
         * @access  public
         * @param   Boolean more
         * @return  Boolean
         */
        setMore: function(more) {
            this._more = more;
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseCollection'], function() {

    /**
     * CollectionItemsCollection
     * 
     * @extends BaseCollection
     */
    window.CollectionItemsCollection = BaseCollection.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'CollectionItemsCollection')
         */
        _string: 'CollectionItemsCollection',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Array dataSet
         * @return  void
         */
        init: function(dataSet) {
            this._super(dataSet);
        },

        /**
         * model
         * 
         * @access  public
         * @param   Object publicData
         * @return  BaseModel
         */
        model: function(publicData) {
            if (publicData.publicId.match(/^vcst/) === null) {
                var model = FrameworkUtils.getModel('Vector');
                return model;
            }
            var model = FrameworkUtils.getModel('VectorSet');
            return model;
        },

        /**
         * map
         * 
         * @access  public
         * @param   Array dataSet
         * @return  Array
         */
        map: function(dataSet) {
            var activeRecords = [];
            for (var publicData of dataSet) {
                var activeRecord = this.model(publicData).setActiveRecord(publicData);
                if (this.contains(activeRecord) === true) {
                    continue;
                }
                activeRecords.push(activeRecord);
                this.add(activeRecord);
            }
            return activeRecords;
        },

        /**
         * vectors
         * 
         * @access  public
         * @return  Array
         */
        vectors: function() {
            var activeRecords = this.filter(function(activeRecord) {
                var publicId = activeRecord.get('publicId');
                if (publicId.match(/^vctr/) !== null) {
                    return true;
                }
                return false;
            });
            return activeRecords;
        },

        /**
         * vectorSets
         * 
         * @access  public
         * @return  Array
         */
        vectorSets: function() {
            var activeRecords = this.filter(function(activeRecord) {
                var publicId = activeRecord.get('publicId');
                if (publicId.match(/^vcst/) !== null) {
                    return true;
                }
                return false;
            });
            return activeRecords;
        }
    });
});
window.DependencyLoader.push(['DatabaseTableCollection', 'CollectionModel'], function() {

    /**
     * CollectionsCollection
     * 
     * @extends DatabaseTableCollection
     */
    window.CollectionsCollection = DatabaseTableCollection.extend({

        /**
         * Properties
         * 
         */

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('Collection'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'CollectionsCollection')
         */
        _string: 'CollectionsCollection',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Array dataSet
         * @return  void
         */
        init: function(dataSet) {
            this._super(dataSet);
        },

        /**
         * created
         * 
         * @access  public
         * @return  Array
         */
        created: function() {
            var activeRecords = this.filter(function(activeRecord) {
                return activeRecord.likes() === false;
            });
            return activeRecords;
        }
    });
});
window.DependencyLoader.push(['BaseCollection'], function() {

    /**
     * DatabaseTableCollection
     * 
     * @fires   add
     * @fires   remove
     * @extends BaseCollection
     */
    window.DatabaseTableCollection = BaseCollection.extend({

        /**
         * Properties
         * 
         */

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: null,

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'DatabaseTableCollection')
         */
        _string: 'DatabaseTableCollection',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Array dataSet
         * @return  void
         */
        init: function(dataSet) {
            this._super(dataSet);
        },

        /**
         * map
         * 
         * @access  public
         * @param   Array dataSet
         * @return  Array
         */
        map: function(dataSet) {
            var activeRecords = [];
            for (var publicData of dataSet) {
                var activeRecord = this._model.setActiveRecord(publicData);
                if (this.contains(activeRecord) === true) {
                    continue;
                }
                activeRecords.push(activeRecord);
                this.add(activeRecord);
            }
            return activeRecords;
        },

        /**
         * model
         * 
         * @access  public
         * @return  BaseModel
         */
        model: function() {
            var model = this._model;
            return model;
        }
    });
});
window.DependencyLoader.push(['DatabaseTableCollection', 'DesignerModel'], function() {

    /**
     * DesignersCollection
     * 
     * @extends DatabaseTableCollection
     */
    window.DesignersCollection = DatabaseTableCollection.extend({

        /**
         * Properties
         * 
         */

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('Designer'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'DesignersCollection')
         */
        _string: 'DesignersCollection',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Array dataSet
         * @return  void
         */
        init: function(dataSet) {
            this._super(dataSet);
        }
    });
});
window.DependencyLoader.push(['DatabaseTableCollection', 'FigmaPluginModel'], function() {

    /**
     * FigmaPluginsCollection
     * 
     * @extends DatabaseTableCollection
     */
    window.FigmaPluginsCollection = DatabaseTableCollection.extend({

        /**
         * Properties
         * 
         */

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('FigmaPlugin'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'FigmaPluginsCollection')
         */
        _string: 'FigmaPluginsCollection',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Array dataSet
         * @return  void
         */
        init: function(dataSet) {
            this._super(dataSet);
        }
    });
});
window.DependencyLoader.push(['DatabaseTableCollection', 'LicenseModel'], function() {

    /**
     * LicensesCollection
     * 
     * @extends DatabaseTableCollection
     */
    window.LicensesCollection = DatabaseTableCollection.extend({

        /**
         * Properties
         * 
         */

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('License'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'LicensesCollection')
         */
        _string: 'LicensesCollection',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Array dataSet
         * @return  void
         */
        init: function(dataSet) {
            this._super(dataSet);
        }
    });
});
window.DependencyLoader.push(['DatabaseTableCollection', 'RedirectModel'], function() {

    /**
     * RedirectsCollection
     * 
     * @extends DatabaseTableCollection
     */
    window.RedirectsCollection = DatabaseTableCollection.extend({

        /**
         * Properties
         * 
         */

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('Redirect'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'RedirectsCollection')
         */
        _string: 'RedirectsCollection',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Array dataSet
         * @return  void
         */
        init: function(dataSet) {
            this._super(dataSet);
        }
    });
});
window.DependencyLoader.push(['DatabaseTableCollection', 'SubsetModel'], function() {

    /**
     * SubsetsCollection
     * 
     * @extends DatabaseTableCollection
     */
    window.SubsetsCollection = DatabaseTableCollection.extend({

        /**
         * Properties
         * 
         */

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('Subset'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'SubsetsCollection')
         */
        _string: 'SubsetsCollection',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Array dataSet
         * @return  void
         */
        init: function(dataSet) {
            this._super(dataSet);
        }
    });
});
window.DependencyLoader.push(['DatabaseTableCollection', 'VectorModel'], function() {

    /**
     * VectorsCollection
     * 
     * @extends DatabaseTableCollection
     */
    window.VectorsCollection = DatabaseTableCollection.extend({

        /**
         * Properties
         * 
         */

        /**
         * _loader
         * 
         * @access  protected
         * @var     null|LoaderTriggerComponentView (default: null)
         */
        _loader: null,

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('Vector'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'VectorsCollection')
         */
        _string: 'VectorsCollection',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Array dataSet
         * @return  void
         */
        init: function(dataSet) {
            this._super(dataSet);
        },

        /**
         * _handleNext
         * 
         * @access  protected
         * @param   VectorActiveRecord current
         * @param   VectorActiveRecord next
         * @return  Promise
         */
        _handleNext: function(current, next) {
            if (next === null) {
                if (this._more === false) {
                    var promise = DataUtils.getPromise(null);
                    return promise;
                }
                if (this._loader === null) {
                    var promise = DataUtils.getPromise(null);
                    return promise;
                }
                var collection = this,
                    promise = this._loader.loadMore().then(function(vectors) {
                        if (vectors.length === 0) {
                            return null;
                        }
                        return collection.next(current);
                    });
                return promise;
            }
            var promise = DataUtils.getPromise(next);
            return promise;
        },

        /**
         * getLoader
         * 
         * @access  public
         * @return  null|LoaderTriggerComponentView
         */
        getLoader: function() {
            var loader = this._loader;
            return loader;
        },

        /**
         * next
         * 
         * @access  public
         * @param   VectorActiveRecord current
         * @return  Promise
         */
        next: function(current) {
            var handler = this._handleNext.bind(this, current),
                promise = this._super(current).then(handler);
            return promise;
        },

        /**
         * setLoader
         * 
         * @access  public
         * @param   LoaderTriggerComponentView loader
         * @return  Boolean
         */
        setLoader: function(loader) {
            this._loader = loader;
            return true;
        }
    });
});
window.DependencyLoader.push(['DatabaseTableCollection', 'VectorSetDesignerModel'], function() {

    /**
     * VectorSetDesignersCollection
     * 
     * @extends DatabaseTableCollection
     */
    window.VectorSetDesignersCollection = DatabaseTableCollection.extend({

        /**
         * Properties
         * 
         */

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('VectorSetDesigner'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'VectorSetDesignersCollection')
         */
        _string: 'VectorSetDesignersCollection',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Array dataSet
         * @return  void
         */
        init: function(dataSet) {
            this._super(dataSet);
        }
    });
});
window.DependencyLoader.push(['DatabaseTableCollection', 'VectorSetModel'], function() {

    /**
     * VectorSetsCollection
     * 
     * @extends DatabaseTableCollection
     */
    window.VectorSetsCollection = DatabaseTableCollection.extend({

        /**
         * Properties
         * 
         */

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('VectorSet'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'VectorSetsCollection')
         */
        _string: 'VectorSetsCollection',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Array dataSet
         * @return  void
         */
        init: function(dataSet) {
            this._super(dataSet);
        }
    });
});
window.DependencyLoader.push(['DatabaseTableCollection', 'VectorSetSubsetModel'], function() {

    /**
     * VectorSetSubsetsCollection
     * 
     * @extends DatabaseTableCollection
     */
    window.VectorSetSubsetsCollection = DatabaseTableCollection.extend({

        /**
         * Properties
         * 
         */

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('VectorSetSubset'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'VectorSetSubsetsCollection')
         */
        _string: 'VectorSetSubsetsCollection',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Array dataSet
         * @return  void
         */
        init: function(dataSet) {
            this._super(dataSet);
        },

        /**
         * categories
         * 
         * @access  public
         * @return  Array
         */
        categories: function() {
            var activeRecords = this.filter(function(activeRecord) {
                return activeRecord.category() === true;
            });
            return activeRecords;
        },

        /**
         * colors
         * 
         * @access  public
         * @return  Array
         */
        colors: function() {
            var activeRecords = this.filter(function(activeRecord) {
                return activeRecord.color() === true;
            });
            return activeRecords;
        },

        /**
         * styles
         * 
         * @access  public
         * @return  Array
         */
        styles: function() {
            var activeRecords = this.filter(function(activeRecord) {
                return activeRecord.style() === true;
            });
            return activeRecords;
        },

        /**
         * types
         * 
         * @access  public
         * @return  Array
         */
        types: function() {
            var activeRecords = this.filter(function(activeRecord) {
                return activeRecord.type() === true;
            });
            return activeRecords;
        },
    });
});
window.DependencyLoader.push(['DatabaseTableCollection', 'VectorSetSubsetVectorModel'], function() {

    /**
     * VectorSetSubsetVectorsCollection
     * 
     * @extends DatabaseTableCollection
     */
    window.VectorSetSubsetVectorsCollection = DatabaseTableCollection.extend({

        /**
         * Properties
         * 
         */

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('VectorSetSubsetVector'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'VectorSetSubsetVectorsCollection')
         */
        _string: 'VectorSetSubsetVectorsCollection',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Array dataSet
         * @return  void
         */
        init: function(dataSet) {
            this._super(dataSet);
        },

        /**
         * colors
         * 
         * @access  public
         * @param   Boolean listLimit (defualt: true)
         * @return  Array
         */
        colors: function(listLimit) {
            listLimit = listLimit === undefined ? true : listLimit;
            var styles = this.filter(function(activeRecord) {
                if (listLimit === true && activeRecord.getVectorSetSubset().list() === false) {
                    return false;
                }
                return activeRecord.getSubset().color() === true;
            });
            return styles;
        },

        /**
         * styles
         * 
         * @access  public
         * @param   Boolean listLimit (defualt: true)
         * @return  Array
         */
        styles: function(listLimit) {
            listLimit = listLimit === undefined ? true : listLimit;
            var styles = this.filter(function(activeRecord) {
                if (listLimit === true && activeRecord.getVectorSetSubset().list() === false) {
                    return false;
                }
                return activeRecord.getSubset().style() === true;
            });
            return styles;
        }
    });
});
window.DependencyLoader.push(['DatabaseTableCollection', 'VendorModel'], function() {

    /**
     * VendorsCollection
     * 
     * @extends DatabaseTableCollection
     */
    window.VendorsCollection = DatabaseTableCollection.extend({

        /**
         * Properties
         * 
         */

        /**
         * _model
         * 
         * @access  protected
         * @var     null|BaseModel
         */
        _model: FrameworkUtils.getModel('Vendor'),

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'VendorsCollection')
         */
        _string: 'VendorsCollection',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   Array dataSet
         * @return  void
         */
        init: function(dataSet) {
            this._super(dataSet);
        }
    });
});
window.DependencyLoader.push(['Class'], function() {

    /**
     * Base
     * 
     * @extends Class
     */
    window.Base = Class.extend({

        /**
         * Properties
         * 
         */

        /**
         * _customEventListeners
         * 
         * @access  protected
         * @var     Object (default: {})
         */
        _customEventListeners: {},

        /**
         * _data
         * 
         * This is a general, all-purpose data store. It can be used to store
         * anything, but as a result, can be used to store too much.
         * 
         * For active records, the publicData property should be used for record
         * data exclusively.
         * 
         * @access  protected
         * @var     Object (default: {})
         */
        _data: {},

        /**
         * _helpers
         * 
         * @access  protected
         * @var     Object (default: {})
         */
        _helpers: {},

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'Base')
         */
        _string: 'Base',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @return  void
         */
        init: function() {
            this._customEventListeners = {};
            this._data = {};
        },

        /**
         * _getHelper
         * 
         * @access  protected
         * @param   String name
         * @return  Base
         */
        _getHelper: function(name) {
            name = (name) + 'Helper';
            this._helpers[name] = this._helpers[name] || new window[name];
            return this._helpers[name];
        },

        /**
         * addCustomEventListener
         * 
         * @access  public
         * @param   String customEventName
         * @param   Function handler
         * @return  Object
         */
        addCustomEventListener: function(customEventName, handler) {
            var customEventListener = {};
            customEventListener.timestamp = new Date().getTime();
            customEventListener.customEventName = customEventName;
            customEventListener.handler = handler;
            customEventListener.iterations = Infinity;
            this._customEventListeners[customEventName] = this._customEventListeners[customEventName] || [];
            this._customEventListeners[customEventName].push(customEventListener);
            return customEventListener;
        },

        /**
         * addCustomEventListenerOnce
         * 
         * @access  public
         * @param   String customEventName
         * @param   Function handler
         * @return  Object
         */
        addCustomEventListenerOnce: function(customEventName, handler) {
            var customEventListener = this.addCustomEventListener(customEventName, handler);
            customEventListener.iterations = 1;
            return customEventListener;
        },

        /**
         * clearCustomEventListeners
         * 
         * @access  public
         * @return  Boolean
         */
        clearCustomEventListeners: function() {
            this._customEventListeners = {};
            return true;
        },

        /**
         * get
         * 
         * @access  public
         * @param   String key
         * @return  mixed
         */
        get: function(key) {
            var data = this._data,
                value = data[key];
            return value;
        },

        /**
         * getCustomEventListener
         * 
         * @access  public
         * @param   String customEventName
         * @return  null|Array
         */
        getCustomEventListener: function(customEventName) {
            var customEventListeners = this.getCustomEventListeners();
            customEventListeners = customEventListeners[customEventName] || [];
            return customEventListeners;
        },

        /**
         * getCustomEventListeners
         * 
         * @access  public
         * @return  Object
         */
        getCustomEventListeners: function() {
            var customEventListeners = this._customEventListeners;
            return customEventListeners;
        },

        /**
         * getData
         * 
         * @access  public
         * @return  Object
         */
        getData: function() {
            var data = this._data;
            return data;
        },

        /**
         * set
         * 
         * @access  public
         * @param   String key
         * @param   mixed value
         * @return  void
         */
        set: function(key, value) {
            this._data[key] = value;
        },

        /**
         * toString
         * 
         * @access  public
         * @return  String
         */
        toString: function() {
            var string = this._string;
            return string;
        },

        /**
         * triggerCustomEvent
         * 
         * @access  public
         * @param   String customEventName
         * @param   undefined|Array args (default: [])
         * @return  void
         */
        triggerCustomEvent: function(customEventName, args) {
            args = args || [];
            EventUtils.triggerCustomEvent(customEventName, this, args);
        }
    });
});
window.DependencyLoader.push(['Base'], function() {

    /**
     * ModalUIModifierHelper
     * 
     * Provides an interface for managing UI modifier attributes and values,
     * specifically in the context of modals.
     * 
     * Abstracted out to a Helper class, since it's easy to compartmentalize.
     * 
     * @extends Base
     */
    window.ModalUIModifierHelper = Base.extend({

        /**
         * Properties
         * 
         */

        /**
         * _modifiers
         * 
         * @access  protected
         * @var     null|Array (default: null)
         */
        _modifiers: null,

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'ModalUIModifierHelper')
         */
        _string: 'ModalUIModifierHelper',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @return  void
         */
        init: function() {
            this._super();
        },

        /**
         * _addUIModifierChangeEventListener
         * 
         * @access  protected
         * @param   HTMLElement $element
         * @return  Boolean
         */
        _addUIModifierChangeEventListener: function($element) {
            var handler = this._handleUIModifierChangeEvent.bind(this);
            if ($element === null) {
                return false;
            }
            $element.addEventListener('change', handler);
            return true;
        },

        /**
         * _getUIModifiers
         * 
         * @access  protected
         * @return  Array
         */
        _getUIModifiers: function() {
            var modifiers = this._data.view.getAttribute('ui-modifiers');
            if (modifiers === null) {
                return [];
            }
            if (this._modifiers === null) {
                modifiers = modifiers.replace(/\s/g, '');
                modifiers = modifiers.split(',');
                this._modifiers = modifiers;;
            }
            modifiers = this._modifiers;
            return modifiers;
        },

        /**
         * _handleUIModifierChangeEvent
         * 
         * @access  protected
         * @param   Object event
         * @return  Boolean
         */
        _handleUIModifierChangeEvent: function(event) {
            this.refreshUIModifierAttribute();
            return true;
        },

        /**
         * refreshUIModifierAttribute
         * 
         * @access  public
         * @return  Boolean
         */
        refreshUIModifierAttribute: function() {
            var modifiers = this._getUIModifiers();
            if (modifiers.length === 0) {
                return false;
            }
            var hashes = [];
            for (var uiModifier of modifiers) {
                var $element = this._data.view.__name(uiModifier)
                if ($element === null) {
                    continue;
                }
                var value = $element.value,
                    hash = (uiModifier) + ':' + (value);
                hashes.push(hash)
            }
            var str = hashes.join(',');
            this._data.view.setAttribute('ui-modifiers', str);
            return true;
        },

        /**
         * setup
         * 
         * @access  public
         * @return  void
         */
        setup: function() {
            var modifiers = this._getUIModifiers();
            if (modifiers.length === 0) {
                return false;
            }
            for (var uiModifier of modifiers) {
                var $element = this._data.view.__name(uiModifier);
                if ($element === null) {
                    continue;
                }
                this._addUIModifierChangeEventListener($element);
            }
            return true;
        },
    });
});
window.DependencyLoader.push(['BaseModel'], function() {

    /**
     * ApplicationModel
     * 
     * @extends BaseModel
     */
    window.ApplicationModel = BaseModel.extend({

        /**
         * Properties
         * 
         */

        /**
         * _apiPath
         * 
         * @access  protected
         * @var     null|String (default: '/api/v2/applications')
         */
        _apiPath: '/api/v2/applications',

        /**
         * _objectTypeKey
         * 
         * @access  protected
         * @var     null|String (default: 'application')
         */
        _objectTypeKey: 'application',

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'ApplicationModel')
         */
        _string: 'ApplicationModel',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @return  void
         */
        init: function() {
            this._super();
        }
    });
});
window.DependencyLoader.push(['BaseModel'], function() {

    /**
     * AssetModel
     * 
     * @extends BaseModel
     */
    window.AssetModel = BaseModel.extend({

        /**
         * Properties
         * 
         */

        /**
         * _apiPath
         * 
         * @access  protected
         * @var     null|String (default: '/api/v2/assets')
         */
        _apiPath: '/api/v2/assets',

        /**
         * _objectTypeKey
         * 
         * @access  protected
         * @var     null|String (default: 'asset')
         */
        _objectTypeKey: 'asset',

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'AssetModel')
         */
        _string: 'AssetModel',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @return  void
         */
        init: function() {
            this._super();
        }
    });
});
window.DependencyLoader.push(['Base'], function() {

    /**
     * BaseModel
     * 
     * @extends Base
     */
    window.BaseModel = Base.extend({

        /**
         * Properties
         * 
         */

        /**
         * _apiPath
         * 
         * @access  protected
         * @var     null|String (default: null)
         */
        _apiPath: null,

        /**
         * _lastResponse
         * 
         * @access  protected
         * @var     null|Object (default: null)
         */
        _lastResponse: null,

        /**
         * _objectTypeKey
         * 
         * @access  protected
         * @var     null|String (default: null)
         */
        _objectTypeKey: null,

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'BaseModel')
         */
        _string: 'BaseModel',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @return  void
         */
        init: function() {
            this._super();
            this._lastResponse = null;
        },

        /**
         * _delete
         * 
         * @access  protected
         * @param   String path
         * @param   undefined|Object data (default: {})
         * @param   undefined|Object options (default: {})
         * @return  Promise
         */
        _delete: function(path, data, options) {
            data = data || {};
            options = options || {};
            var method = 'delete',
                promise = this._request(path, method, data, options);
            return promise;
        },

        /**
         * _get
         * 
         * @access  protected
         * @param   String path
         * @param   undefined|Object data (default: {})
         * @param   undefined|Object options (default: {})
         * @return  Promise
         */
        _get: function(path, data, options) {
            data = data || {};
            options = options || {};
            var method = 'get',
                promise = this._request(path, method, data, options);
            return promise;
        },

        /**
         * _getCreatePath
         * 
         * @access  protected
         * @return  String
         */
        _getCreatePath: function() {
            var apiPath = this._apiPath,
                path = apiPath;
            return path;
        },

        /**
         * _getDeletePath
         * 
         * @access  protected
         * @param   BaseActiveRecord activeRecord
         * @return  String
         */
        _getDeletePath: function(activeRecord) {
            var apiPath = this._apiPath,
                publicId = activeRecord.get('publicId'),
                path = (apiPath) + '/' + (publicId);
            return path;
        },

        /**
         * _getListPath
         * 
         * @access  protected
         * @return  String
         */
        _getListPath: function() {
            var apiPath = this._apiPath,
                path = apiPath;
            return path;
        },

        /**
         * _getReadPath
         * 
         * @access  protected
         * @param   BaseActiveRecord activeRecord
         * @return  String
         */
        _getReadPath: function(activeRecord) {
            var apiPath = this._apiPath,
                publicId = activeRecord.get('publicId'),
                path = (apiPath) + '/' + (publicId);
            return path;
        },

        /**
         * _getUpdatePath
         * 
         * @access  protected
         * @param   BaseActiveRecord activeRecord
         * @return  String
         */
        _getUpdatePath: function(activeRecord) {
            var apiPath = this._apiPath,
                publicId = activeRecord.get('publicId'),
                path = (apiPath) + '/' + (publicId);
            return path;
        },

        /**
         * _handleCreateRequestResponse
         * 
         * @access  protected
         * @param   Object response
         * @return  Promise
         */
        _handleCreateRequestResponse: function(response) {
            if (response.data === undefined) {
                var errors = response.errors,
                    promise = DataUtils.getPromise(errors);
                return promise;
            }
            var publicData = response.data.object,
                activeRecord = this.setActiveRecord(publicData),
                promise = DataUtils.getPromise(activeRecord);
            return promise;
        },

        /**
         * _handleDeleteRequestResponse
         * 
         * @access  protected
         * @param   BaseActiveRecord activeRecord
         * @param   Object response
         * @return  Promise
         */
        _handleDeleteRequestResponse: function(activeRecord, response) {
            var promise = DataUtils.getPromise(activeRecord);
            return promise;
        },

        /**
         * _handleListRequestResponse
         * 
         * @access  protected
         * @param   Object response
         * @return  Promise
         */
        _handleListRequestResponse: function(response) {
            var activeRecords = [],
                objects = response.data.objects;
            for (var object of objects) {
                var activeRecord = this.setActiveRecord(object);
                activeRecords.push(activeRecord);
            }
            var promise = DataUtils.getPromise(activeRecords);
            return promise;
        },

        /**
         * _handleReadRequestResponse
         * 
         * @access  protected
         * @param   Object response
         * @return  Promise
         */
        _handleReadRequestResponse: function(response) {
            var publicData = response.data.object,
                activeRecord = this.setActiveRecord(publicData),
                promise = DataUtils.getPromise(activeRecord);
            return promise;
        },

        /**
         * _handleRequestResponse
         * 
         * @access  protected
         * @param   Object response
         * @return  Promise
         */
        _handleRequestResponse: function(response) {
            this._lastResponse = response;
            var promise = DataUtils.getPromise(response);
            return promise;
        },

        /**
         * _handleUpdateRequestResponse
         * 
         * @access  protected
         * @param   Object response
         * @return  Promise
         */
        _handleUpdateRequestResponse: function(response) {
            var publicData = response.data.object,
                activeRecord = this.setActiveRecord(publicData),
                promise = DataUtils.getPromise(activeRecord);
            return promise;
        },

        /**
         * _patch
         * 
         * @access  protected
         * @param   String path
         * @param   undefined|Object data (default: {})
         * @param   undefined|Object options (default: {})
         * @return  Promise
         */
        _patch: function(path, data, options) {
            data = data || {};
            options = options || {};
            var method = 'patch',
                promise = this._request(path, method, data, options);
            return promise;
        },

        /**
         * _request
         * 
         * @access  protected
         * @param   String path
         * @param   String method
         * @param   undefined|Object data (default: {})
         * @param   undefined|Object options (default: {})
         * @return  Promise
         */
        _request: function(path, method, data, options) {
            data = data || {};
            options = options || {};
            var handler = this._handleRequestResponse.bind(this),
                promise = RequestUtils.request(path, method, data, options).then(handler);
            return promise;
        },

        /**
         * create
         * 
         * @access  public
         * @param   undefined|Object data (default: {})
         * @param   undefined|Object options (default: {})
         * @return  Promise
         */
        create: function(data, options) {
            data = data || {};
            options = options || {};
            var path = this._getCreatePath(),
                handler = this._handleCreateRequestResponse.bind(this),
                promise = this.post(path, data, options).then(handler);
            return promise;
        },

        /**
         * delete
         * 
         * @access  public
         * @param   BaseActiveRecord activeRecord
         * @param   undefined|Object options (default: {})
         * @return  Promise
         */
        delete: function(activeRecord, options) {
            options = options || {};
            var path = this._getDeletePath(activeRecord),
                data = {},
                handler = this._handleDeleteRequestResponse.bind(this, activeRecord),
                promise = this._delete(path, data, options).then(handler);
            return promise;
        },

        /**
         * get
         * 
         * @access  public
         * @param   BaseActiveRecord activeRecord
         * @param   undefined|Object data (default: {})
         * @param   undefined|Object options (default: {})
         * @return  Promise
         */
        get: function(activeRecord, data, options) {
            data = data || {};
            options = options || {};
            var path = this._getReadPath(activeRecord),
                handler = this._handleReadRequestResponse.bind(this),
                promise = this._get(path, data, options).then(handler);
            return promise;
        },

        /**
         * getAPIPath
         * 
         * @access  public
         * @return  String
         */
        getAPIPath: function() {
            var apiPath = this._apiPath;
            return apiPath;
        },

        /**
         * getLastResponse
         * 
         * @access  public
         * @return  null|Object
         */
        getLastResponse: function() {
            var response = this._lastResponse;
            return response;
        },

        /**
         * list
         * 
         * @access  public
         * @param   undefined|Object data (default: {})
         * @param   undefined|Object options (default: {})
         * @return  Promise
         */
        list: function(data, options) {
            data = data || {};
            options = options || {};
            var path = this._getListPath(),
                handler = this._handleListRequestResponse.bind(this),
                promise = this._get(path, data, options).then(handler);
            return promise;
        },

        /**
         * post
         * 
         * @access  public
         * @param   String path
         * @param   undefined|Object data (default: {})
         * @param   undefined|Object options (default: {})
         * @return  Promise
         */
        post: function(path, data, options) {
            data = data || {};
            options = options || {};
            var method = 'post',
                promise = this._request(path, method, data, options);
            return promise;
        },

        /**
         * setActiveRecord
         * 
         * @access  public
         * @param   String|Object publicData
         * @return  BaseActiveRecord
         */
        setActiveRecord: function(publicData) {
            if (typeof publicData === 'string') {
                var publicId = publicData;
                publicData = {};
                publicData.publicId = publicId;
            }
            var publicId = publicData.publicId,
                objectTypeKey = this._objectTypeKey,
                objectType = DataUtils.ucfirst(objectTypeKey),
                name = objectType,
                activeRecord = FrameworkUtils.setActiveRecord(publicId, name, publicData);
            return activeRecord;
        },

        /**
         * update
         * 
         * @access  public
         * @param   BaseActiveRecord activeRecord
         * @param   undefined|Object data (default: {})
         * @param   undefined|Object options (default: {})
         * @return  Promise
         */
        update: function(activeRecord, data, options) {
            data = data || {};
            options = options || {};
            var path = this._getUpdatePath(activeRecord),
                handler = this._handleUpdateRequestResponse.bind(this),
                promise = this._patch(path, data, options).then(handler);
            return promise;
        }
    });
});
window.DependencyLoader.push(['BaseModel'], function() {

    /**
     * CollectionModel
     * 
     * @extends BaseModel
     */
    window.CollectionModel = BaseModel.extend({

        /**
         * Properties
         * 
         */

        /**
         * _apiPath
         * 
         * @access  protected
         * @var     null|String (default: '/api/v2/collections')
         */
        _apiPath: '/api/v2/collections',

        /**
         * _objectTypeKey
         * 
         * @access  protected
         * @var     null|String (default: 'collection')
         */
        _objectTypeKey: 'collection',

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'CollectionModel')
         */
        _string: 'CollectionModel',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @return  void
         */
        init: function() {
            this._super();
        },

        /**
         * _handleAdd
         * 
         * @access  protected
         * @param   Object response
         * @return  Object
         */
        _handleAdd: function(response) {
            var publicData = response.data.object;
            this.setActiveRecord(publicData);
            return response;
        },

        /**
         * _handleRemove
         * 
         * @access  protected
         * @param   Object response
         * @return  Object
         */
        _handleRemove: function(response) {
            var publicData = response.data.object;
            this.setActiveRecord(publicData);
            return response;
        },

        /**
         * add
         * 
         * @access  public
         * @param   CollectionActiveRecord collection
         * @param   BaseActiveRecord activeRecord
         * @return  Promise
         */
        add: function(collection, activeRecord) {
            var publicId = collection.get('publicId'),
                path = (this._apiPath) + '/' + (publicId) + '/add',
                data = {},
                handler = this._handleAdd.bind(this);
            data.item = activeRecord.get('publicId');
            var request = this.post(path, data).then(handler);
            return request;
        },

        /**
         * remove
         * 
         * @access  public
         * @param   CollectionActiveRecord collection
         * @param   BaseActiveRecord activeRecord
         * @return  Promise
         */
        remove: function(collection, activeRecord) {
            var publicId = collection.get('publicId'),
                path = (this._apiPath) + '/' + (publicId) + '/remove',
                data = {},
                handler = this._handleRemove.bind(this);
            data.item = activeRecord.get('publicId');
            var request = this.post(path, data).then(handler);
            return request;
        }
    });
});
window.DependencyLoader.push(['BaseModel'], function() {

    /**
     * CrashModel
     * 
     * @extends BaseModel
     */
    window.CrashModel = BaseModel.extend({

        /**
         * Properties
         * 
         */

        /**
         * _apiPath
         * 
         * @access  protected
         * @var     null|String (default: '/api/v2/crashes')
         */
        _apiPath: '/api/v2/crashes',

        /**
         * _objectTypeKey
         * 
         * @access  protected
         * @var     null|String (default: 'crash')
         */
        _objectTypeKey: 'crash',

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'CrashModel')
         */
        _string: 'CrashModel',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @return  void
         */
        init: function() {
            this._super();
        }
    });
});
window.DependencyLoader.push(['BaseModel'], function() {

    /**
     * DesignerModel
     * 
     * @extends BaseModel
     */
    window.DesignerModel = BaseModel.extend({

        /**
         * Properties
         * 
         */

        /**
         * _apiPath
         * 
         * @access  protected
         * @var     null|String (default: '/api/v2/designers')
         */
        _apiPath: '/api/v2/designers',

        /**
         * _objectTypeKey
         * 
         * @access  protected
         * @var     null|String (default: 'designer')
         */
        _objectTypeKey: 'designer',

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'DesignerModel')
         */
        _string: 'DesignerModel',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @return  void
         */
        init: function() {
            this._super();
        }
    });
});
window.DependencyLoader.push(['BaseModel'], function() {

    /**
     * FigmaPluginModel
     * 
     * @extends BaseModel
     */
    window.FigmaPluginModel = BaseModel.extend({

        /**
         * Properties
         * 
         */

        /**
         * _apiPath
         * 
         * @access  protected
         * @var     null|String (default: '/api/v2/figmaPlugins')
         */
        _apiPath: '/api/v2/figmaPlugins',

        /**
         * _objectTypeKey
         * 
         * @access  protected
         * @var     null|String (default: 'figmaPlugin')
         */
        _objectTypeKey: 'figmaPlugin',

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'FigmaPluginModel')
         */
        _string: 'FigmaPluginModel',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @return  void
         */
        init: function() {
            this._super();
        }
    });
});
window.DependencyLoader.push(['BaseModel'], function() {

    /**
     * FingerprintModel
     * 
     * @extends BaseModel
     */
    window.FingerprintModel = BaseModel.extend({

        /**
         * Properties
         * 
         */

        /**
         * _apiPath
         * 
         * @access  protected
         * @var     null|String (default: '/api/v2/fingerprints')
         */
        _apiPath: '/api/v2/fingerprints',

        /**
         * _objectTypeKey
         * 
         * @access  protected
         * @var     null|String (default: 'fingerprint')
         */
        _objectTypeKey: 'fingerprint',

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'FingerprintModel')
         */
        _string: 'FingerprintModel',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @return  void
         */
        init: function() {
            this._super();
        }
    });
});
window.DependencyLoader.push(['BaseModel'], function() {

    /**
     * LicenseModel
     * 
     * @extends BaseModel
     */
    window.LicenseModel = BaseModel.extend({

        /**
         * Properties
         * 
         */

        /**
         * _apiPath
         * 
         * @access  protected
         * @var     null|String (default: '/api/v2/licenses')
         */
        _apiPath: '/api/v2/licenses',

        /**
         * _objectTypeKey
         * 
         * @access  protected
         * @var     null|String (default: 'license')
         */
        _objectTypeKey: 'license',

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'LicenseModel')
         */
        _string: 'LicenseModel',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @return  void
         */
        init: function() {
            this._super();
        }
    });
});
window.DependencyLoader.push(['BaseModel'], function() {

    /**
     * RedirectModel
     * 
     * @extends BaseModel
     */
    window.RedirectModel = BaseModel.extend({

        /**
         * Properties
         * 
         */

        /**
         * _apiPath
         * 
         * @access  protected
         * @var     null|String (default: '/api/v2/redirects')
         */
        _apiPath: '/api/v2/redirects',

        /**
         * _objectTypeKey
         * 
         * @access  protected
         * @var     null|String (default: 'redirect')
         */
        _objectTypeKey: 'redirect',

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'RedirectModel')
         */
        _string: 'RedirectModel',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @return  void
         */
        init: function() {
            this._super();
        }
    });
});
window.DependencyLoader.push(['BaseModel'], function() {

    /**
     * SubsetModel
     * 
     * @extends BaseModel
     */
    window.SubsetModel = BaseModel.extend({

        /**
         * Properties
         * 
         */

        /**
         * _apiPath
         * 
         * @access  protected
         * @var     null|String (default: '/api/v2/subsets')
         */
        _apiPath: '/api/v2/subsets',

        /**
         * _objectTypeKey
         * 
         * @access  protected
         * @var     null|String (default: 'subset')
         */
        _objectTypeKey: 'subset',

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'SubsetModel')
         */
        _string: 'SubsetModel',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @return  void
         */
        init: function() {
            this._super();
        }
    });
});
window.DependencyLoader.push(['BaseModel'], function() {

    /**
     * UpgradeModel
     * 
     * @extends BaseModel
     */
    window.UpgradeModel = BaseModel.extend({

        /**
         * Properties
         * 
         */

        /**
         * _apiPath
         * 
         * @access  protected
         * @var     null|String (default: '/api/v2/upgrades')
         */
        _apiPath: '/api/v2/upgrades',

        /**
         * _objectTypeKey
         * 
         * @access  protected
         * @var     null|String (default: 'upgrade')
         */
        _objectTypeKey: 'upgrade',

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'UpgradeModel')
         */
        _string: 'UpgradeModel',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @return  void
         */
        init: function() {
            this._super();
        }
    });
});
window.DependencyLoader.push(['BaseModel'], function() {

    /**
     * UserModel
     * 
     * @extends BaseModel
     */
    window.UserModel = BaseModel.extend({

        /**
         * Properties
         * 
         */

        /**
         * _apiPath
         * 
         * @access  protected
         * @var     null|String (default: '/api/v2/users')
         */
        _apiPath: '/api/v2/users',

        /**
         * _objectTypeKey
         * 
         * @access  protected
         * @var     null|String (default: 'user')
         */
        _objectTypeKey: 'user',

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'UserModel')
         */
        _string: 'UserModel',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @return  void
         */
        init: function() {
            this._super();
        },

        /**
         * logout
         * 
         * @access  public
         * @return  Promise
         */
        logout: function() {
            var path = '/auth/logout',
                promise = this.post(path);
            return promise;
        }
    });
});
window.DependencyLoader.push(['BaseModel'], function() {

    /**
     * UserEmailTemplateModel
     * 
     * @extends BaseModel
     */
    window.UserEmailTemplateModel = BaseModel.extend({

        /**
         * Properties
         * 
         */

        /**
         * _apiPath
         * 
         * @access  protected
         * @var     null|String (default: '/api/v2/userEmailTemplates')
         */
        _apiPath: '/api/v2/userEmailTemplates',

        /**
         * _objectTypeKey
         * 
         * @access  protected
         * @var     null|String (default: 'userEmailTemplate')
         */
        _objectTypeKey: 'userEmailTemplate',

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'UserEmailTemplateModel')
         */
        _string: 'UserEmailTemplateModel',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @return  void
         */
        init: function() {
            this._super();
        }
    });
});
window.DependencyLoader.push(['BaseModel'], function() {

    /**
     * VectorModel
     * 
     * @extends BaseModel
     */
    window.VectorModel = BaseModel.extend({

        /**
         * Properties
         * 
         */

        /**
         * _apiPath
         * 
         * @access  protected
         * @var     null|String (default: '/api/v2/vectors')
         */
        _apiPath: '/api/v2/vectors',

        /**
         * _objectTypeKey
         * 
         * @access  protected
         * @var     null|String (default: 'vector')
         */
        _objectTypeKey: 'vector',

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'VectorModel')
         */
        _string: 'VectorModel',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @return  void
         */
        init: function() {
            this._super();
        }
    });
});
window.DependencyLoader.push(['BaseModel'], function() {

    /**
     * VectorSetModel
     * 
     * @extends BaseModel
     */
    window.VectorSetModel = BaseModel.extend({

        /**
         * Properties
         * 
         */

        /**
         * _apiPath
         * 
         * @access  protected
         * @var     null|String (default: '/api/v2/vectorSets')
         */
        _apiPath: '/api/v2/vectorSets',

        /**
         * _objectTypeKey
         * 
         * @access  protected
         * @var     null|String (default: 'vectorSet')
         */
        _objectTypeKey: 'vectorSet',

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'VectorSetModel')
         */
        _string: 'VectorSetModel',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @return  void
         */
        init: function() {
            this._super();
        }
    });
});
window.DependencyLoader.push(['BaseModel'], function() {

    /**
     * VectorSetDesignerModel
     * 
     * @extends BaseModel
     */
    window.VectorSetDesignerModel = BaseModel.extend({

        /**
         * Properties
         * 
         */

        /**
         * _apiPath
         * 
         * @access  protected
         * @var     null|String (default: '/api/v2/vectorSetDesigners')
         */
        _apiPath: '/api/v2/vectorSetDesigners',

        /**
         * _objectTypeKey
         * 
         * @access  protected
         * @var     null|String (default: 'vectorSetDesigner')
         */
        _objectTypeKey: 'vectorSetDesigner',

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'VectorSetDesignerModel')
         */
        _string: 'VectorSetDesignerModel',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @return  void
         */
        init: function() {
            this._super();
        }
    });
});
window.DependencyLoader.push(['BaseModel'], function() {

    /**
     * VectorSetSubsetModel
     * 
     * @extends BaseModel
     */
    window.VectorSetSubsetModel = BaseModel.extend({

        /**
         * Properties
         * 
         */

        /**
         * _apiPath
         * 
         * @access  protected
         * @var     null|String (default: '/api/v2/vectorSetSubsets')
         */
        _apiPath: '/api/v2/vectorSetSubsets',

        /**
         * _objectTypeKey
         * 
         * @access  protected
         * @var     null|String (default: 'vectorSetSubset')
         */
        _objectTypeKey: 'vectorSetSubset',

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'VectorSetSubsetModel')
         */
        _string: 'VectorSetSubsetModel',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @return  void
         */
        init: function() {
            this._super();
        }
    });
});
window.DependencyLoader.push(['BaseModel'], function() {

    /**
     * VectorSetSubsetVectorModel
     * 
     * @extends BaseModel
     */
    window.VectorSetSubsetVectorModel = BaseModel.extend({

        /**
         * Properties
         * 
         */

        /**
         * _apiPath
         * 
         * @access  protected
         * @var     null|String (default: '/api/v2/vectorSetSubsetVectors')
         */
        _apiPath: '/api/v2/vectorSetSubsetVectors',

        /**
         * _objectTypeKey
         * 
         * @access  protected
         * @var     null|String (default: 'vectorSetSubsetVector')
         */
        _objectTypeKey: 'vectorSetSubsetVector',

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'VectorSetSubsetVectorModel')
         */
        _string: 'VectorSetSubsetVectorModel',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @return  void
         */
        init: function() {
            this._super();
        }
    });
});
window.DependencyLoader.push(['BaseModel'], function() {

    /**
     * VendorModel
     * 
     * @extends BaseModel
     */
    window.VendorModel = BaseModel.extend({

        /**
         * Properties
         * 
         */

        /**
         * _apiPath
         * 
         * @access  protected
         * @var     null|String (default: '/api/v2/vendors')
         */
        _apiPath: '/api/v2/vendors',

        /**
         * _objectTypeKey
         * 
         * @access  protected
         * @var     null|String (default: 'vendor')
         */
        _objectTypeKey: 'vendor',

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'VendorModel')
         */
        _string: 'VendorModel',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @return  void
         */
        init: function() {
            this._super();
        }
    });
});

/**
 * AdminUtils
 * 
 * @abstract
 */
window.AdminUtils = (function() {

    /**
     * Properties (private)
     * 
     */

    /**
     * __string
     * 
     * @access  private
     * @var     String (default: 'AdminUtils')
     */
    var __string = 'AdminUtils';

    /**
     * Methods (private)
     * 
     */

    /**
     * __getAuthPayload
     * 
     * @access  private
     * @return  null|Object
     */
    var __getAuthPayload = function() {
        var user = AuthUtils.getUser();
        if (user === null) {
            return null;
        }
        var authPayload = {};
        authPayload.user = {};
        authPayload.user.publicId = user.get('publicId');
        return authPayload;
    };

    /**
     * Methods (public)
     * 
     */
    return {

        /**
         * addVectorKeyboardShortcutEventListener
         * 
         * @access  public
         * @return  Boolean
         */
        // addVectorKeyboardShortcutEventListener: function() {
        //     if (AuthUtils.admin() === false) {
        //         return false;
        //     }
        //     return true;
        // },

        /**
         * log
         * 
         * @access  public
         * @param   String msg
         * @param   undefined|Object payload (default: undefined)
         * @return  Boolean
         */
        log: function(msg, payload) {
            var path = '/utils/log',
                method = 'post',
                data = {},
                payload = payload || {};
            data.msg = msg;
            payload.auth = __getAuthPayload();
            payload = JSON.stringify(payload);
            data.payload = payload;
            RequestUtils.request(path, method, data);
            return true;
        }
    };
})();

/**
 * ArrayUtils
 * 
 * @access  public
 * @var     Object
 */
window.ArrayUtils = (function() {

    /**
     * Properties (private)
     * 
     */

    /**
     * __string
     * 
     * @access  private
     * @var     String (default: 'ArrayUtils')
     */
    var __string = 'ArrayUtils';

    /**
     * Methods (public)
     * 
     */
    return {

        /**
         * remove
         * 
         * @see     https://stackoverflow.com/questions/5767325/how-can-i-remove-a-specific-item-from-an-array
         * @access  public
         * @param   Array arr
         * @param   mixed item
         * @return  Boolean
         */
        remove: function(arr, item) {
            var index = arr.indexOf(item);
            if (index > -1) {
                arr.splice(index, 1);
                return true;
            }
            return false;
        }
    };
})();

/**
 * AudioUtils
 * 
 * @abstract
 */
window.AudioUtils = (function() {

    /**
     * Properties (private)
     * 
     */

    /**
     * __string
     * 
     * @access  private
     * @var     String (default: 'AudioUtils')
     */
    var __string = 'AudioUtils';

    /**
     * Methods (private)
     * 
     */

    /**
     * __getAudioSourceURLs
     * 
     * @access  private
     * @param   String basename
     * @return  Array
     */
    var __getAudioSourceURLs = function(basename) {
        var urls = [],
            host = ConfigUtils.getHost(),
            url = 'https://' + (host) + '/iconduck/static/audio/' + (basename);
        urls.push(url);
        return urls;
    };

    /**
     * __playSounds
     * 
     * @access  private
     * @return  Boolean
     */
    var __playSounds = function() {
        // if (Config.getRole() === 'local') {
        //     return false;
        // }
        // if (Config.getRole() === 'dev') {
        //     return false;
        // }
        // if (Config.getRole() === 'prod') {
        //     return false;
        // }
        // if (AuthUtils.admin() === true) {
        //     return true;
        // }
        return true;
        // return false;
    };

    /**
     * Methods (public)
     * 
     */
    return {

        /**
         * play
         * 
         * @access  public
         * @param   String basename
         * @return  Boolean
         */
        play: function(basename) {
            if (__playSounds() === false) {
                return false;
            }
            var urls = __getAudioSourceURLs(basename),
                options = {};
            options.src = urls;
            var howl = new Howl(options);
            howl.play();
            return true;
        }
    };
})();

/**
 * AuthUtils
 * 
 * @abstract
 */
window.AuthUtils = (function() {

    /**
     * Properties (private)
     * 
     */

    /**
     * __string
     * 
     * @access  private
     * @var     String (default: 'AuthUtils')
     */
    var __string = 'AuthUtils';

    /**
     * __user
     * 
     * @access  private
     * @var     null|UserActiveRecord (default: null)
     */
    var __user = null;

    /**
     * Methods (public)
     * 
     */
    return {

        /**
         * admin
         * 
         * @access  public
         * @return  Boolean
         */
        admin: function() {
            var user = AuthUtils.getUser();
            if (user === null) {
                return false;
            }
            var admin = user.admin();
            return admin;
        },

        /**
         * feature
         * 
         * Returns the feature value corresponding to the plan the client is
         * "on".
         * 
         * @access  public
         * @param   String featureKey
         * @return  mixed
         */
        feature: function(featureKey) {
            var planKey = 'guest';
            if (AuthUtils.getUser() !== null) {
                planKey = 'free';
            }
            if (AuthUtils.upgraded() === true) {
                planKey = 'pro';
            }
            var plans = ConfigUtils.getPublicValue('plans'),
                plan = plans[planKey],
                value = plan.features[featureKey];
            return value;
        },

        /**
         * getDownloadCount
         * 
         * @access  public
         * @return  Number
         */
        getDownloadCount: function() {
            if (AuthUtils.getUser() === null) {
                var downloadCount = Cookies.get('client-downloadCount');
                if (downloadCount === undefined) {
                    downloadCount = 0;
                }
                downloadCount = downloadCount.toInt();
                return downloadCount
            }
            var downloadCount = AuthUtils.getUser().get('downloadCount').toInt();
            return downloadCount;
        },

        /**
         * getMaxDownloadCount
         * 
         * @access  public
         * @return  Number
         */
        getMaxDownloadCount: function() {
            if (AuthUtils.getUser() === null) {
                var maxDownloadCount = ConfigUtils.getPublicValue('plans', 'guest', 'maxDownloadCount');
            } else if (AuthUtils.upgraded() === false) {
                var maxDownloadCount = ConfigUtils.getPublicValue('plans', 'free', 'maxDownloadCount');
            } else if (AuthUtils.upgraded() === true) {
                var maxDownloadCount = ConfigUtils.getPublicValue('plans', 'pro', 'maxDownloadCount');
            }
            if (maxDownloadCount === 0) {
                maxDownloadCount = Infinity;
            }
            if (maxDownloadCount !== Infinity) {
                maxDownloadCount = maxDownloadCount.toInt();
            }
            return maxDownloadCount;
        },

        /**
         * getUser
         * 
         * @access  public
         * @return  null|UserActiveRecord
         */
        getUser: function() {
            var user = __user;
            return user;
        },

        /**
         * login
         * 
         * @access  public
         * @param   UserActiveRecord user
         * @return  Boolean
         */
        login: function(user) {
            AuthUtils.setUser(user);
            var args = [user];
            __Iconduck.page.triggerCustomEvent('auth/login', args);
            return true;
        },

        /**
         * logout
         * 
         * @access  public
         * @return  Boolean
         */
        logout: function() {
            __Iconduck.page.triggerCustomEvent('auth/logout');
            return true;
        },

        /**
         * setUser
         * 
         * @access  public
         * @param   UserActiveRecord user
         * @return  Boolean
         */
        setUser: function(user) {
            __user = user;
            __Iconduck.page.triggerCustomEvent('user/set');
            if (AuthUtils.admin() === true) {
                __Iconduck.page.triggerCustomEvent('user/set/admin');
            }
            return true;
        },

        /**
         * syncUser
         * 
         * @access  public
         * @return  Boolean
         */
        syncUser: function() {
            var user = AuthUtils.getUser();
            if (user === null) {
                return false;
            }
            var force = true;
            user.read(force);
            return true;
        },

        /**
         * upgraded
         * 
         * @access  public
         * @return  Boolean
         */
        upgraded: function() {
            var user = AuthUtils.getUser();
            if (user === null) {
                return false;
            }
            var upgraded = user.upgraded();
            return upgraded;
        }
    };
})();

/**
 * AuthPromptUtils
 * 
 * @abstract
 */
window.AuthPromptUtils = (function() {

    /**
     * Properties (private)
     * 
     */

    /**
     * __properties
     * 
     * @access  private
     * @var     Object
     */
    var __properties = {
        maxDownloadCountExceeded: {
            copy: {
                primary: 'Please sign up to continue',
                secondary: 'To download more than **5** icons, you will need to log into your Iconduck account.'
            },
            graphic: {
                icon: {
                    className: 'icon-download'
                }
            }
        },
        collections: {
            copy: {
                primary: 'Please sign up to continue',
                secondary: 'To use our Collections feature, you will need to log into your Iconduck account.'
            },
            graphic: {
                icon: {
                    className: 'icon-folder-open'
                }
            }
        },
        likes: {
            copy: {
                primary: 'Please sign up to continue',
                secondary: 'To use our Likes feature, you will need to log into your Iconduck account.'
            },
            graphic: {
                icon: {
                    className: 'icon-heart'
                }
            }
        }
    };

    /**
     * __string
     * 
     * @access  private
     * @var     String (default: 'AuthPromptUtils')
     */
    var __string = 'AuthPromptUtils';

    /**
     * Methods (private)
     * 
     */

    /**
     * __getCopy
     * 
     * @access  private
     * @param   String authPromptKey
     * @return  Object
     */
    var __getCopy = function(authPromptKey) {
        var copy = {},
            primary = __properties[authPromptKey].copy.primary,
            secondary = __properties[authPromptKey].copy.secondary;
        primary = primary.replace(/\*\*([^\*]+)\*\*/g, '<strong>$1</strong>');
        secondary = secondary.replace(/\*\*([^\*]+)\*\*/g, '<strong>$1</strong>');
        copy.primary = primary;
        copy.secondary = secondary;
        return copy;
    };

    /**
     * __getProperties
     * 
     * @access  private
     * @param   String authPromptKey
     * @return  Object
     */
    var __getProperties = function(authPromptKey) {
        var properties = {};
        properties.copy = __getCopy(authPromptKey);
        properties.graphic = __properties[authPromptKey].graphic;
        return properties;
    };

    /**
     * Methods (public)
     * 
     */
    return {

        /**
         * getProperties
         * 
         * @access  public
         * @param   String authPromptKey
         * @return  Boolean
         */
        getProperties: function(authPromptKey) {
            var properties = __getProperties(authPromptKey);
            return properties;
        }
    };
})();

/**
 * ConfigUtils
 * 
 * @abstract
 */
window.ConfigUtils = (function() {

    /**
     * Methods (private)
     * 
     */

    /**
     * __overrideValue
     * 
     * @access  private
     * @param   Array keys
     * @param   mixed value
     * @return  mixed
     */
    var __overrideValue = function(keys, value) {
        if (AuthUtils.admin() === false) {
            return value;
        }
        var key = keys.join('.', keys);
        if (key === 'uiux.formModalDelay') {
            return 0;
        }
        if (key === 'uiux.formProcessingDelay') {
            return 0;
        }
        if (key === 'uiux.mailingListAutoShowDelay') {
            return 0;
        }
        return value;
    };

    /**
     * Properties (private)
     * 
     */

    /**
     * __data
     * 
     * @access  private
     * @var     Object (default: {})
     */
    var __data = {};

    /**
     * __string
     * 
     * @access  private
     * @var     String (default: 'ConfigUtils')
     */
    var __string = 'ConfigUtils';

    /**
     * Methods (public)
     * 
     */
    return {

        /**
         * getAdminValue
         * 
         * @access  public
         * @return  mixed
         */
        getAdminValue: function() {
            var keys = Array.from(arguments),
                value = __data;
            keys.unshift('admin');
            for (var key of keys) {
                value = value[key];
            }
            value = __overrideValue(keys, value);
            return value;
        },

        /**
         * getAPIEndpoint
         * 
         * @access  public
         * @param   String path
         * @return  String
         */
        getAPIEndpoint: function(path) {
            var host = ConfigUtils.getAPIHost(),
                url = 'https://' + (host) + (path);
            return url;
        },

        /**
         * getAPIHost
         * 
         * @access  public
         * @return  String
         */
        getAPIHost: function() {
            var host = ConfigUtils.getPublicValue('hosts', 'api');
            return host;
        },

        /**
         * getCloudinaryHost
         * 
         * @access  public
         * @return  String
         */
        // getCloudinaryHost: function() {
        //     var host = ConfigUtils.getPublicValue('hosts', 'cloudinary');
        //     return host;
        // },

        /**
         * getHost
         * 
         * @access  public
         * @return  String
         */
        getHost: function() {
            var host = ConfigUtils.getPublicValue('hosts', 'app');
            return host;
        },

        /**
         * getPublicValue
         * 
         * @access  public
         * @return  mixed
         */
        getPublicValue: function() {
            var keys = Array.from(arguments),
                value = __data;
            keys.unshift('public');
            for (var key of keys) {
                value = value[key];
            }
            value = __overrideValue(keys, value);
            return value;
        },

        /**
         * getRole
         * 
         * @access  public
         * @return  String
         */
        getRole: function() {
            var role = ConfigUtils.getPublicValue('role');
            return role;
        },

        /**
         * getStaticAssetURL
         * 
         * @access  public
         * @param   String path
         * @return  String
         */
        getStaticAssetURL: function(path) {
            var host = ConfigUtils.getStaticHost(),
                cacheBust = ConfigUtils.getStaticAssetCacheBust(),
                // url = 'https://' + (host) + (path) + '?cb=' + (cacheBust);
                url = 'https://' + (host) + (path);
            return url;
        },

        /**
         * getStaticHost
         * 
         * @access  public
         * @return  String
         */
        getStaticHost: function() {
            var host = ConfigUtils.getPublicValue('hosts', 'static');
            return host;
        },

        /**
         * setAdminData
         * 
         * @access  public
         * @param   Object data
         * @return  Boolean
         */
        setAdminData: function(data) {
            __data.admin = data;
            var customEventName = 'config/admin/loaded';
            __Iconduck.page.triggerCustomEvent(customEventName);
            return true;
        },

        /**
         * setPublicData
         * 
         * @note    Not firing a config/public/loaded event (like you might
         *          expect) because __Iconduck.page isn't available for
         *          triggering custom events at the point that this method is
         *          called.
         * @access  public
         * @param   Object data
         * @return  Boolean
         */
        setPublicData: function(data) {
            __data.public = data;
            return true;
        }
    };
})();

/**
 * CookieUtils
 * 
 * @todo    Add a way to access server cookies from here
 * @access  public
 * @var     Object
 */
window.CookieUtils = (function() {

    /**
     * Properties (private)
     * 
     */

    /**
     * __string
     * 
     * @access  private
     * @var     String (default: 'CookieUtils')
     */
    var __string = 'CookieUtils';

    /**
     * Methods (private)
     * 
     */

    /**
     * __getCookieKey
     * 
     * @access  private
     * @param   String key
     * @param   String prefix
     * @return  Array
     */
    var __getCookieKey = function(key, prefix) {
        if (prefix === 'client') {
            key = (prefix) + '-' + (key);
            return key;
        }
        var cookieShortcodes = ConfigUtils.getPublicValue('cookieShortcodes');
        key = (prefix) + ':' + (key);
        key = cookieShortcodes[key].shortcode;
        return key;
    };

    /**
     * Methods (public)
     * 
     */
    return {

        /**
         * get
         * 
         * @access  public
         * @param   String key
         * @param   undefined|String prefix
         * @return  mixed
         */
        get: function(key, prefix) {
            var prefix = prefix || 'client';
            key = __getCookieKey(key, prefix);
            var response = Cookies.get(key);
            if (response === undefined) {
                return undefined;
            }
            if (prefix === 'server') {
                return response;
            }
            response = JSON.parse(response);
            return response;
        },

        /**
         * increment
         * 
         * @access  public
         * @param   String key
         * @return  void
         */
        increment: function(key) {
            var response = CookieUtils.get(key) || 0;
            response += 1;
            CookieUtils.set(key, response);
        },

        /**
         * set
         * 
         * @access  public
         * @param   String key
         * @param   mixed value
         * @param   undefined|String prefix
         * @return  void
         */
        set: function(key, value, prefix) {
            var prefix = prefix || 'client';
            key = __getCookieKey(key, prefix);
            value = JSON.stringify(value);
            var properties = {};
            properties.expires = 365 * 10;
            Cookies.set(key, value, properties);
        }
    };
})();

/**
 * DataUtils
 * 
 * @access  public
 * @var     Object
 */
window.DataUtils = (function() {

    /**
     * Properties (private)
     * 
     */

    /**
     * __store
     * 
     * @access  private
     * @var     Object (default: {})
     */
    var __store = {};

    /**
     * __string
     * 
     * @access  private
     * @var     String (default: 'DataUtils')
     */
    var __string = 'DataUtils';

    /**
     * Methods (public)
     * 
     */
    return {

        /**
         * delay
         * 
         * @access  public
         * @param   Number milliseconds
         * @return  Promise
         */
        delay: function(milliseconds) {
            var promise = new Promise(function(resolve, reject) {
                setTimeout(function() {
                    resolve();
                }, milliseconds);
            });
            return promise;
        },

        /**
         * escapeString
         * 
         * @access  public
         * @param   String str
         * @return  String
         */
        escapeString: function(str) {
            str = str.replace('"', '&quot;');
            return str;
        },

        /**
         * formatNumber
         * 
         * @access  public
         * @param   Number numb
         * @return  String
         */
        formatNumber: function(numb) {
            var str = numb.toLocaleString();
            return str;
        },

        /**
         * getPromise
         * 
         * @access  public
         * @param   mixed value
         * @return  Promise
         */
        getPromise: function(value) {
            var promise = new Promise(function(resolve, reject) {
                resolve(value);
            });
            return promise;
        },

        /**
         * getRandom
         * 
         * @see     https://stackoverflow.com/questions/5915096/get-a-random-item-from-a-javascript-array
         * @access  public
         * @param   Array arr
         * @return  mixed
         */
        getRandom: function(arr) {
            return arr[Math.floor(Math.random()*arr.length)];
        },

        /**
         * store
         * 
         * @access  public
         * @var     Object
         */
        store: {

            /**
             * get
             * 
             * @access  public
             * @param   String key
             * @return  mixed
             */
            get: function(key) {
                var value = __store[key];
                return value;
            },

            /**
             * set
             * 
             * @access  public
             * @param   String key
             * @param   mixed value
             * @return  void
             */
            set: function(key, value) {
                __store[key] = value;
            }
        },

        /**
         * sort
         * 
         * @see     https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort
         * @access  public
         * @param   String propertyKey
         * @param   BaseActiveRecord a
         * @param   BaseActiveRecord b
         * @return  Number
         */
        sort: function(propertyKey, a, b) {
            if (typeof a[propertyKey] === 'function') {
                var first = a[propertyKey]().toLowerCase(),
                    second = b[propertyKey]().toLowerCase()
            } else {
                var first = a.get(propertyKey).toLowerCase(),
                    second = b.get(propertyKey).toLowerCase()
            }
            if (first < second) {
                return -1;
            }
            if (first > second) {
                return 1;
            }
            return 0;
        },

        /**
         * touch
         * 
         * @see     https://stackoverflow.com/a/4819886/115025
         * @link    https://developer.mozilla.org/en-US/docs/Web/CSS/@media
         * @access  public
         * @return  Boolean
         */
        touch: function() {
            if (window.matchMedia('(pointer: coarse)').matches === true) {
                return true;
            }
            return false;
        },

        /**
         * ucfirst
         * 
         * @access  public
         * @param   String str
         * @return  String
         */
        ucfirst: function(str) {
            str = str.charAt(0).toUpperCase() + str.slice(1);
            return str;
        }
    };
})();

/**
 * DateTimeUtils
 * 
 * @access  public
 * @var     Object
 */
window.DateTimeUtils = (function() {

    /**
     * Properties (private)
     * 
     */

    /**
     * __string
     * 
     * @access  private
     * @var     String (default: 'DateTimeUtils')
     */
    var __string = 'DateTimeUtils';

    /**
     * Methods (public)
     * 
     */
    return {

        /**
         * current
         * 
         * @access  public
         * @return  Number
         */
        current: function() {
            var currentTimestamp = Date.now();
            currentTimestamp = currentTimestamp / 1000;
            currentTimestamp = Math.floor(currentTimestamp);
            return currentTimestamp;
        }
    };
})();

/**
 * DynamicElementUtils
 * 
 * This utility class is responsible for attaching active record listeners for
 * various HTML elements on the page to ensure their respective "states" (aka.
 * anchor text, attributes, etc) are kept in sync with active record values.
 * 
 * @example data-dynamic="vector:vctr00000001,text:name"
 *          Becomes:
 *          data-dynamic="modelName:vector,publicId:vctr00000001,watch:name,set:text,output:name"
 * 
 * @example data-dynamic="vector:vctr00000001,watch:name,text:getName()"
 *          Becomes:
 *          data-dynamic="modelName:vector,publicId:vctr00000001,watch:name,set:text,output:getName()"
 * 
 * @example data-dynamic="vector:vctr00000001,watch:name,set:text,output:name"
 *          Becomes:
 *          data-dynamic="modelName:vector,publicId:vctr00000001,watch:name,set:text,output:name"
 * 
 * @example data-dynamic="vector:vctr00000001,watch:name,set:text,output:getName()"
 *          Becomes:
 *          data-dynamic="modelName:vector,publicId:vctr00000001,watch:name,set:text,output:getName()"
 * 
 * @example data-dynamic="modelName:vector,publicId:vctr00000001,watch:name,set:text,output:name"
 * @example data-dynamic="modelName:vector,publicId:vctr00000001,watch:name,set:text,output:getName()"
 * @access  public
 * @var     Object
 */
window.DynamicElementUtils = (function() {

    /**
     * Properties (private)
     * 
     */

    /**
     * __string
     * 
     * @access  private
     * @var     String (default: 'DynamicElementUtils')
     */
    var __string = 'DynamicElementUtils';

    /**
     * Methods (private)
     * 
     */

    /**
     * __getDynamicElementActiveRecord
     * 
     * @access  private
     * @param   HTMLElement $element
     * @return  BaseActiveRecord
     */
    var __getDynamicElementActiveRecord = function($element) {
        var dynamic = $element.data.dynamic,
            model = dynamic.model,
            publicId = dynamic.publicId,
            activeRecord = model.setActiveRecord(publicId);
        return activeRecord;
    };

    /**
     * __getInitialNormalizedDynamicMap
     * 
     * @access  private
     * @param   HTMLElement $element
     * @return  Object
     */
    var __getInitialNormalizedDynamicMap = function($element) {
        var dynamicValue = $element.getAttribute('data-dynamic'),
            pairs = dynamicValue.split(','),
            map = {};
        for (var pair of pairs) {
            var pieces = pair.split(':'),
                key = pieces[0],
                value = pieces[1];
            map[key] = value;
        }
        return map
    };

    /**
     * __getNormalizedDynamicMap
     * 
     * @access  private
     * @param   HTMLElement $element
     * @return  Object
     */
    var __getNormalizedDynamicMap = function($element) {

        // Created the object
        var map = __getInitialNormalizedDynamicMap($element);

        // Set model
        var modelName = map.modelName;
        if (!('model' in map)) {
            var keys = Object.keys(map),
                modelName = keys[0];
        }
        map.model = FrameworkUtils.getModel(modelName);

        // Set publicId
        var publicId = map.publicId || map[modelName];
        map.publicId = publicId;

        // Set watch
        map.watch = map.watch || map.text;

        // Set "set"
        if ('text' in map) {
            // map.watch = map.text;
            map.set = 'text';
            // map.output = map.text;
            // delete map.text;
        }

        // Set output
        map.output = map.output || map.text;

        // Done
        delete map.text;
        return map;
    };

    /**
     * __getOutputValue
     * 
     * @access  private
     * @param   HTMLElement $element
     * @return  mixed
     */
    var __getOutputValue = function($element) {
        var dynamic = $element.data.dynamic,
            output = dynamic.output,
            activeRecord = __getDynamicElementActiveRecord($element);
        if (output.match(/\(/) === null) {
            var value = activeRecord.get(output);
            return value;
        }
        output = output.replace(/\(.+$/, '');
        var value = activeRecord[output]();
        return value;
    };

    /**
     * __handleChangeCustomEvent
     * 
     * @access  private
     * @param   HTMLElement $element
     * @param   mixed newValue
     * @return  Boolean
     */
    var __handleChangeCustomEvent = function($element, newValue) {
        var dynamic = $element.data.dynamic,
            set = dynamic.set,
            value = __getOutputValue($element);
        if (set === 'text') {
            $element.innerText = value;
        }
        return true;
    };

    /**
     * __normalizeDynamicProperties
     * 
     * @access  private
     * @param   HTMLElement $element
     * @return  Boolean
     */
    var __normalizeDynamicProperties = function($element) {
        var dynamic = __getNormalizedDynamicMap($element);
        $element.data = $element.data || {};
        $element.data.dynamic = dynamic;
        $element.removeAttribute('data-dynamic');
        return true;
    };

    /**
     * __setupDynamicElement
     * 
     * @access  private
     * @param   HTMLElement $element
     * @return  Boolean
     */
    var __setupDynamicElement = function($element) {
        var dynamic = $element.data.dynamic;
        if (dynamic.watch !== undefined) {
            var activeRecord = __getDynamicElementActiveRecord($element),
                columnKey = dynamic.watch,
                customEventName = 'change/' + (columnKey),
                handler = __handleChangeCustomEvent.bind(activeRecord, $element);
            activeRecord.addCustomEventListener(customEventName, handler);
            return true;
        }
        if (dynamic.listen !== undefined) {
            var activeRecord = __getDynamicElementActiveRecord($element),
                customEventName = dynamic.listen,
                handler = __handleChangeCustomEvent.bind(activeRecord, $element);
            activeRecord.addCustomEventListener(customEventName, handler);
            return true;
        }
        return false;
    };

    /**
     * Methods (public)
     * 
     */
    return {

        /**
         * setup
         * 
         * @access  public
         * @param   BaseView view
         * @return  Boolean
         */
        setup: function(view) {
            var $elements = view.__data('dynamic', true);
            for (var $element of $elements) {
                __normalizeDynamicProperties($element);
                __setupDynamicElement($element);
            }
            return true;
        }
    };
})();

/**
 * ElementUtils
 * 
 * @abstract
 */
window.ElementUtils = (function() {

    /**
     * Properties (private)
     * 
     */

    /**
     * __string
     * 
     * @access  private
     * @var     String (default: 'ElementUtils')
     */
    var __string = 'ElementUtils';

    /**
     * Methods (public)
     * 
     */
    return {

        /**
         * getTemplateMarkup
         * 
         * @access  public
         * @param   String templateName
         * @param   undefined|Object data (default: {})
         * @return  String
         */
        getTemplateMarkup: function(templateName, data) {
            var setupComponent = false,
                $element = ElementUtils.renderTemplate(templateName, data, setupComponent),
                markup = $element.outerHTML;
            return markup;
        },

        /**
         * renderTemplate
         * 
         * @access  public
         * @param   String templateName
         * @param   undefined|Object data (default: {})
         * @param   undefined|Boolean setupComponent (default: true)
         * @return  HTMLElement
         */
        renderTemplate: function(templateName, data, setupComponent) {
            data = data || {};
            data.data = data;
            var template = FrameworkUtils.getTemplate(templateName),
                compiler = _.template(template),
                markup = compiler(data).trim(),
                div = document.createElement('div');
            div.innerHTML = markup.trim();
            var $element = div.firstChild;
            if (setupComponent !== false) {
                FrameworkUtils.setupComponent($element, data);
            }
            return $element;
        },

        /**
         * visible
         * 
         * @see     https://stackoverflow.com/questions/19669786/check-if-element-is-visible-in-dom
         * @access  public
         * @param   HTMLElement $element
         * @return  Boolean
         */
        visible: function($element) {
            var visible = $element.offsetParent !== null;
            return visible;
        }
    };
})();

/**
 * ElementHideStackUtils
 * 
 * This utility class is responsible for managing hiding elements based on user
 * behaviour. The behaviour (at the time of documentation) is limited to a user
 * using the escape key, or pressing anywhere in the app to hide/destroy an
 * element (eg. a modal or popover).
 * 
 * This was abstracted out to this class to clean up classes, but also to ensure
 * a complicated flow (namely, a hierarchy of "hidable" elements) could be
 * organized efficiently.
 * 
 * @abstract
 */
window.ElementHideStackUtils = (function() {

    /**
     * Properties (private)
     * 
     */

    /**
     * __stack
     * 
     * @access  private
     * @var     Array (default: [])
     */
    var __stack = [];

    /**
     * __string
     * 
     * @access  private
     * @var     String (default: 'ElementHideStackUtils')
     */
    var __string = 'ElementHideStackUtils';

    /**
     * Methods (public)
     * 
     */
    return {

        /**
         * attempt
         * 
         * @access  public
         * @param   Event event
         * @return  Boolean
         */
        attempt: function(event) {
            var entry = ElementHideStackUtils.last();
            if (entry === null) {
                return false;
            }
            var reference = entry.reference;
            if (reference.validElementHideEvent(event) === false) {
                return false;
            }
            var response = ElementHideStackUtils.run();
            return response;
        },

        /**
         * last
         * 
         * @see     https://stackoverflow.com/questions/3216013/get-the-last-item-in-an-array
         * @see     https://i.imgur.com/MBlQwtG.jpg
         * @access  public
         * @return  null|Object
         */
        last: function() {
            var length = __stack.length,
                index = length - 1,
                entry = __stack[index];
            if (entry === undefined) {
                return null;
            }
            return entry;
        },

        /**
         * pop
         * 
         * @access  public
         * @return  null|Object
         */
        pop: function() {
            var entry = __stack.pop();
            if (entry === undefined) {
                return null;
            }
            return entry;
        },

        /**
         * push
         * 
         * @access  public
         * @param   BaseView reference
         * @param   Function handler
         * @return  Boolean
         */
        push: function(reference, handler) {
            var entry = {};
            entry.reference = reference;
            entry.handler = handler;
            __stack.push(entry);
            return true;
        },

        /**
         * remove
         * 
         * @access  public
         * @param   BaseView reference
         * @return  Boolean
         */
        remove: function(reference) {
            for (var entry of __stack) {
                if (entry.reference === reference) {
                    var response = ArrayUtils.remove(__stack, entry);
                    return response;
                }
            }
            return false;
        },

        /**
         * run
         * 
         * @access  public
         * @return  Boolean
         */
        run: function() {
            var entry = ElementHideStackUtils.pop();
            if (entry === null) {
                return false;
            }
            var reference = entry.reference;
            if (reference.visible() === false) {
                return false;
            }
            reference.triggerCustomEvent('elementHideStackUtils/run');
            var handler = entry.handler;
            handler.apply(reference);
            return true;
        },

        /**
         * stack
         * 
         * @access  public
         * @return  Boolean
         */
        stack: function() {
            var stack = __stack;
            return stack;
        }
    };
})();

/**
 * EventUtils
 * 
 * @access  public
 * @var     Object
 */
window.EventUtils = (function() {

    /**
     * Properties (private)
     * 
     */

    /**
     * __string
     * 
     * @access  private
     * @var     String (default: 'EventUtils')
     */
    var __string = 'EventUtils';

    /**
     * Methods (public)
     * 
     */
    return {

        /**
         * triggerCustomEvent
         * 
         * @access  public
         * @param   String customEventName
         * @param   BaseView target
         * @param   undefined|Array args (default: [])
         * @return  Boolean
         */
        triggerCustomEvent: function(customEventName, target, args) {
            args = args || [];
            LogUtils.log.object(target, customEventName);
            var customEventListeners = target.getCustomEventListener(customEventName);
            for (var customEventListener of customEventListeners) {
                var iterations = customEventListener.iterations;
                if (iterations === 0) {
                    continue;
                }
                customEventListener.iterations--;
                var handler = customEventListener.handler.bind(target);
                handler.apply(target, args);
            }
            return true;
        }
    };
})();

/**
 * FrameworkUtils
 * 
 * @abstract
 */
window.FrameworkUtils = (function() {

    /**
     * Properties (private)
     * 
     */

    /**
     * __pageView
     * 
     * @access  private
     * @var     null|BasePageView (default: null)
     */
    var __pageView = null;

    /**
     * __store
     * 
     * @access  private
     * @var     Object (default: {})
     */
    var __store = {};

    /**
     * __string
     * 
     * @access  private
     * @var     String (default: 'FrameworkUtils')
     */
    var __string = 'FrameworkUtils';

    /**
     * __views
     * 
     * @access  private
     * @var     Array (default: [])
     */
    var __views = [];

    /**
     * Methods (private)
     * 
     */

    /**
     * __getComponentViewConstructorName
     * 
     * @access  private
     * @param   String componentName
     * @return  undefined|Object
     */
    var __getComponentViewConstructorName = function(componentName) {
        var className = DataUtils.ucfirst(componentName),
            constructorName = (className) + 'ComponentView';
        var constructor = window[constructorName];
        if (constructor === undefined) {
            return undefined;
        }
        return constructorName;
    };

    /**
     * __getPageViewName
     * 
     * @access  private
     * @return  String
     */
    var __getPageViewName = function() {
        var $html = document.querySelector('html'),
            viewName = $html.getAttribute('data-view') || 'BasePageView';
        return viewName;
    };

    /**
     * __getViewByName
     * 
     * @access  private
     * @param   String viewName
     * @return  BaseView|null
     */
    var __getViewByName = function(viewName) {
        var views = __views;
        for (var index in views) {
            var view = views[index];
            if (view.toString() === viewName) {
                return view;
            }
        }
        return null;
    };

    /**
     * __setupAdminComponentTemplates
     * 
     * @access  private
     * @return  void
     */
    var __setupAdminComponentTemplates = function() {
        var templates = ConfigUtils.getAdminValue('templates'),
            pattern = /data-template-name="([^"]+)/i;
        for (var template of templates) {
            var matches = template.match(pattern);
            if (matches === null) {
                continue;
            }
            var name = matches.pop();
            __store.templates = __store.templates || {};
            __store.templates[name] = template;
        }
    };

    /**
     * __setupPageView
     * 
     * @access  private
     * @param   HTMLElement $element
     * @return  Boolean
     */
    var __setupPageView = function($element) {
        var $html = document.querySelector('html'),
            constructorName = __getPageViewName(),
            pageView = new window[constructorName]($html);
        __pageView = pageView;
        return true;
    };

    /**
     * __setupPublicComponentTemplates
     * 
     * @access  private
     * @return  Boolean
     */
    var __setupPublicComponentTemplates = function() {
        var templates = ConfigUtils.getPublicValue('templates'),
            pattern = /data-template-name="([^"]+)/i;
        for (var template of templates) {
            var matches = template.match(pattern);
            if (matches === null) {
                continue;
            }
            var name = matches.pop();
            __store.templates = __store.templates || {};
            __store.templates[name] = template;
        }
        return true;
    };

    /**
     * Methods (public)
     * 
     */
    return {

        /**
         * init
         * 
         * @access  public
         * @return  void
         */
        init: function() {
            __setupPublicComponentTemplates();
            __setupPageView();
        },

        /**
         * setupAdminComponentTemplates
         * 
         * @access  public
         * @return  Boolean
         */
        setupAdminComponentTemplates: function() {
            __setupAdminComponentTemplates();
            return true;
        },

        /**
         * destroyComponent
         * 
         * @access  public
         * @param   BaseComponentView component
         * @return  Boolean
         */
        destroyComponent: function(component) {
            var views = __views;
            for (var index in views) {
                var view = views[index];
                if (view === component) {
                    views.splice(index, 1);
                    return true;
                }
            }
            return false;
        },

        /**
         * getActiveRecord
         * 
         * @access  public
         * @param   String publicId
         * @return  null|BaseActiveRecord
         */
        getActiveRecord: function(publicId) {
            if (__store.activeRecords === undefined) {
                return null;
            }
            if (__store.activeRecords[publicId] === undefined) {
                return null;
            }
            var activeRecord = __store.activeRecords[publicId];
            return activeRecord;
        },

        /**
         * getActiveRecords
         * 
         * @access  public
         * @return  Array
         */
        getActiveRecords: function() {
            var activeRecords = __store.activeRecords;
            return activeRecords;
        },

        /**
         * getComponentView
         * 
         * @access  public
         * @param   String componentName
         * @return  BaseComponentView|null
         */
        getComponentView: function(componentName) {
            var viewName = (componentName) + 'ComponentView',
                viewName = DataUtils.ucfirst(viewName),
                view = __getViewByName(viewName);
            return view;
        },

        /**
         * getModel
         * 
         * @access  public
         * @param   String modelKey
         * @return  null|BaseModel
         */
        getModel: function(modelKey) {
            __store.models = __store.models || {};
            var constructorName = DataUtils.ucfirst(modelKey) + 'Model',
                model = __store.models[modelKey] = __store.models[modelKey] || new window[constructorName]();
            return model;
        },

        /**
         * getPageView
         * 
         * @access  public
         * @return  BasePageView
         */
        getPageView: function() {
            var pageView = __pageView;
            return pageView;
        },

        /**
         * getStore
         * 
         * @access  public
         * @return  Object
         */
        getStore: function() {
            var store = __store;
            return store;
        },

        /**
         * getTemplate
         * 
         * @throws  Error
         * @access  public
         * @param   String name
         * @return  String
         */
        getTemplate: function(name) {
            var templates = __store.templates || {},
                template = templates[name] || null;
            if (template === null) {
                var msg = 'Could not find template by name: ' + (name);
                throw new Error(msg);
            }
            return template;
        },

        /**
         * getViews
         * 
         * @access  public
         * @return  Array
         */
        getViews: function() {
            var views = __views;
            return views;
        },

        /**
         * setActiveRecord
         * 
         * @access  public
         * @param   String publicId
         * @param   String name
         * @param   undefined|Object publicData (default: {})
         * @return  BaseActiveRecord
         */
        setActiveRecord: function(publicId, name, publicData) {
            publicData = publicData || {};
            publicData.publicId = publicId;
            var activeRecord = FrameworkUtils.getActiveRecord(publicId);
            if (activeRecord === null) {
                var constructorName = (name) + 'ActiveRecord';
                __store.activeRecords = __store.activeRecords || {};
                __store.activeRecords[publicId] = new window[constructorName](publicData);
                activeRecord = __store.activeRecords[publicId];
                return activeRecord;
            }
            activeRecord.merge(publicData);
            activeRecord.reloadActiveRecords();
            activeRecord.reloadCollections();
            return activeRecord;
        },

        /**
         * setActiveRecords
         * 
         * @access  public
         * @param   String name
         * @param   Array dataSet
         * @return  Array
         */
        setActiveRecords: function(name, dataSet) {
            var activeRecords = [];
            for (var publicData of dataSet) {
                var publicId = publicData.publicId,
                    activeRecord = FrameworkUtils.setActiveRecord(publicId, name, publicData);
                activeRecords.push(activeRecord);
            }
            return activeRecords;
        },

        /**
         * setupComponent
         * 
         * @access  public
         * @param   HTMLElement $component
         * @param   undefined|Object data (default: {})
         * @return  null|BaseComponentView
         */
        setupComponent: function($component, data) {
            data = data || {};
            var setup = $component.getAttribute('data-component-setup');
            if (setup !== null) {
                return null;
            }
            $component.setAttribute('data-component-setup', '1');
            var componentName = $component.getAttribute('data-component-name'),
                constructorName = __getComponentViewConstructorName(componentName);
            if (constructorName === undefined) {
                return null;
            }
            var view = new window[constructorName]($component, data);
            __views.push(view);
            return view;
        },

        /**
         * setupComponents
         * 
         * @access  public
         * @param   HTMLElement $element
         * @return  Array
         */
        setupComponents: function($element) {
            var views = [],
                selector = '[data-component-name]:not([data-component-setup="1"])',
                $components = $element.querySelectorAll(selector);
            for (var $component of $components) {
                var view = FrameworkUtils.setupComponent($component);
                if (view === null) {
                    continue;
                }
                views.push(view);
            }
            return views;
        }
    };
})();

/**
 * LogUtils
 * 
 * @abstract
 * @access  public
 */
window.LogUtils = (function() {

    /**
     * Properties
     * 
     */

    /**
     * __colors
     * 
     * @see     http://www.w3schools.com/cssref/css_colornames.asp
     * @access  private
     * @var     Object
     */
    var __colors = {
        'className' : {
            'BaseActiveRecord':     'orange',
            'BaseCollection':       'red',
            'BaseModel':            'brown',
            'BaseView':             'blue'
        },
        'fallback':   'crimson'
    };

    /**
     * __string
     * 
     * @access  private
     * @var     String (default: 'LogUtils')
     */
    var __string = 'LogUtils';

    /**
     * Methods
     * 
     */

    /**
     * __format
     * 
     * @access  private
     * @param   Object obj
     * @param   mixed msg
     * @return  Array
     */
    var __format = function(obj, msg) {
        var type = obj.toString(),
            color = __getColor(obj),
            msgs = [];
        msgs.push('%c ' + (type));
        msgs.push('color:' + (color) + ';');
        msgs.push(msg);
        return msgs;
    };

    /**
     * __getColor
     * 
     * @access  private
     * @param   Object obj
     * @return  String
     */
    var __getColor = function(obj) {
        for (var className in __colors.className) {
            if (obj instanceof window[className] === true) {
                var color = __colors.className[className];
                return color;
            }
        }
        var color = __colors.fallback;
        return color;
    };

    /**
     * __getTimestamp
     * 
     * Returns a string which represents the timestamp, up to the microsecond.
     * 
     * @access  private
     * @return  String
     */
    // var __getTimestamp = function() {
    //     var timestamp = moment().format('HH:mm:ss (0.SSSS)');
    //     return timestamp;
    // };

    /**
     * __log
     * 
     * @access  private
     * @return  Boolean
     */
    var __log = function() {
        var debugging = ConfigUtils.getPublicValue('uiux', 'debugging');
        return debugging;
    };

    /**
     * __writeToConsole
     * 
     * @access  private
     * @param   Array arr
     * @return  Boolean
     */
    var __writeToConsole = function(arr) {
        if (window.console === undefined) {
            return false;
        }
        if (window.console.log === undefined) {
            return false;
        }
        window.console.log.apply(window.console, arr);
        return true;
    };

    // Public
    return {

        /**
         * Methods
         * 
         */

        /**
         * log
         * 
         * @access  public
         * @var     Object
         */
        log: {

            /**
             * object
             * 
             * @access  public
             * @param   Object obj
             * @param   undefined|mixed msg (default: '(no message)')
             * @return  Boolean
             */
            object: function(obj, msg) {
                if (__log() === false) {
                    return false;
                }
                msg = __format(obj, msg);
                __writeToConsole(msg);
                return false;
            }
        }
    };
})();

/**
 * ModalUtils
 * 
 * @access  public
 * @var     Object
 */
window.ModalUtils = (function() {

    /**
     * Properties (private)
     * 
     */

    /**
     * __string
     * 
     * @access  private
     * @var     String (default: 'ModalUtils')
     */
    var __string = 'ModalUtils';

    /**
     * __visibleModalsCount
     * 
     * @access  private
     * @var     Number (default: 0)
     */
    var __visibleModalsCount = 0;

    /**
     * Methods (private)
     * 
     */

    /**
     * __drawModal
     * 
     * @note    The document.body.appendChild needed to only run when it hadn't
     *          already before run. I was being clever before, which resulted in
     *          previous modals have their scroll offset reset (and any previous
     *          modal being scrolled back to the top, losing context).
     * @access  private
     * @param   String modalKey
     * @param   Object data
     * @return  HTMLElement
     */
    var __drawModal = function(modalKey, data) {
        var templateName = DataUtils.ucfirst(modalKey),
            templateName = (templateName) + 'ModalComponent',
            $modal = ElementUtils.renderTemplate(templateName, data),
            $modals = document.body.querySelector('div.modals');
        if ($modals === null) {
            $modals = document.createElement('div');
            $modals.classList.add('modals');
            document.body.appendChild($modals);
        }
        $modals.appendChild($modal);
        return $modal;
    };

    /**
     * Methods (public)
     * 
     */
    return {

        /**
         * closeLastVisible
         * 
         * @access  public
         * @param   undefined|Boolean onlyEscapable (default: false)
         * @return  Boolean
         */
        closeLastVisible: function(onlyEscapable) {
            var modal = ModalUtils.getLastVisible(onlyEscapable);
            if (modal === null) {
                return false;
            }
            modal.destroy();
            return true;
        },

        /**
         * closeVisible
         * 
         * @access  public
         * @param   undefined|Boolean onlyEscapable (default: false)
         * @return  Boolean
         */
        closeVisible: function(onlyEscapable) {
            var openModalComponentViews = ModalUtils.getVisible(onlyEscapable);
            for (var openModalComponentView of openModalComponentViews) {
                openModalComponentView.destroy();
            }
            return true;
        },

        /**
         * getBusy
         * 
         * @access  public
         * @return  null|BusyModalComponentView
         */
        getBusy: function() {
            var modalComponentView = ModalUtils.getModal('busy');
            return modalComponentView;
        },

        /**
         * getLastVisible
         * 
         * @access  public
         * @param   undefined|Boolean onlyEscapable (default: false)
         * @return  null|BaseModalComponentView
         */
        getLastVisible: function(onlyEscapable) {
            var openModalComponentViews = ModalUtils.getVisible(onlyEscapable);
            if (openModalComponentViews.length === 0) {
                return null;
            }
            var length = openModalComponentViews.length,
                modal = openModalComponentViews[length - 1];
            return modal;
        },

        /**
         * getModal
         * 
         * @access  public
         * @param   String modalKey
         * @return  null|BaseModalComponentView
         */
        getModal: function(modalKey) {
            var modals = ModalUtils.getVisible(),
                componentKey = (modalKey) + 'Modal',
                componentKey = DataUtils.ucfirst(componentKey);
            for (var modal of modals) {
                var $element = modal.getElement(),
                    componentName = $element.getAttribute('data-component-name');
                if (componentName === componentKey) {
                    return modal;
                }
            }
            return null;
        },

        /**
         * getPreview
         * 
         * @access  public
         * @return  null|PreviewModalComponentView
         */
        getPreview: function() {
            var modalComponentView = ModalUtils.getModal('preview');
            return modalComponentView;
        },

        /**
         * getSpotlight
         * 
         * @access  public
         * @return  null|SpotlightModalComponentView
         */
        getSpotlight: function() {
            var modalComponentView = ModalUtils.getModal('spotlight');
            return modalComponentView;
        },

        /**
         * getVisible
         * 
         * @access  public
         * @param   undefined|Boolean onlyEscapable (default: false)
         * @return  Array
         */
        getVisible: function(onlyEscapable) {
            if (onlyEscapable === undefined) {
                onlyEscapable = false;
            }
            var views = FrameworkUtils.getViews(),
                openModalComponentViews = [];
            for (var view of views) {
                var str = view.toString();
                if (str.match(/ModalComponentView$/) === null) {
                    continue;
                }
                if (onlyEscapable === false) {
                    openModalComponentViews.push(view);
                    continue;
                }
                if (view.escapable() === true) {
                    openModalComponentViews.push(view);
                }
            }
            return openModalComponentViews;
        },

        /**
         * getVisibleCount
         * 
         * @access  public
         * @return  Number
         */
        getVisibleCount: function() {
            var visibleCount = __visibleModalsCount;
            return visibleCount;
        },

        /**
         * hideBusy
         * 
         * @access  public
         * @return  Boolean
         */
        hideBusy: function() {
            var modal = ModalUtils.getBusy();
            if (modal === null) {
                return false;
            }
            if (modal.visible() === false) {
                return false;
            }
            // UserAgentUtils.unfreeze();
            modal.destroy();
            return true;
        },

        /**
         * freezeVisible
         * 
         * @access  public
         * @return  Boolean
         */
        freezeVisible: function() {
            var visible = ModalUtils.getVisible();
            if (visible.length === 0) {
                return false;
            }
            for (var modal of visible) {
                modal.freeze();
            }
            return true;
        },

        /**
         * show
         * 
         * @access  public
         * @param   String modalKey
         * @param   undefined|Object data (default: {})
         * @return  BaseModalComponentView
         */
        show: function(modalKey, data) {
            data = data || {};
            var $modal = __drawModal(modalKey, data),
                view = $modal.getView();
            view.show();
            ++__visibleModalsCount;
            view.setAttribute('order', __visibleModalsCount);
            view.addCustomEventListenerOnce('destroy', function() {
                --__visibleModalsCount;
                document.body.querySelector('div.modals').setAttribute('data-component-layer', __visibleModalsCount);
            });
            document.body.querySelector('div.modals').setAttribute('data-component-layer', __visibleModalsCount);
            return view;
        },

        /**
         * showAddCollectionItems
         * 
         * @access  public
         * @param   VectorActiveRecord vector
         * @return  Promise
         */
        showAddCollectionItems: function(vector) {
            ModalUtils.showBusy();
            var promise = vector.read(false).then(function() {
                var data = {};
                data.vector = vector;
                ModalUtils.hideBusy();
                var modalKey = 'AddCollectionItems',
                    modal = ModalUtils.show(modalKey, data);
                return modal;
            });
            return promise;
        },

        /**
         * showAddVectorSetVectors
         * 
         * @access  public
         * @param   VectorSetActiveRecord vectorSet
         * @return  Promise
         */
        showAddVectorSetVectors: function(vectorSet) {
            ModalUtils.showBusy();
            var promise = vectorSet.read().then(function() {
                var data = {};
                data.vectorSet = vectorSet;
                ModalUtils.hideBusy();
                var modalKey = 'AddVectorSetVectors',
                    modal = ModalUtils.show(modalKey, data);
                return modal;
            });
            return promise;
        },

        /**
         * showAlert
         * 
         * @example ModalUtils.showAlert('primary', 'secondary')
         * @access  public
         * @param   String primary
         * @param   String secondary
         * @return  AlertModalComponentView
         */
        showAlert: function(primary, secondary) {
            var data = {};
            data.headlines = {};
            data.headlines.primary = primary;
            data.headlines.secondary = secondary;
            var modal = ModalUtils.show('alert', data);
            return modal;
        },

        /**
         * showAPI
         * 
         * @access  public
         * @return  Boolean
         */
        showAPI: function() {
            var modal = ModalUtils.show('API');
            return modal;
        },

        /**
         * showAuth
         * 
         * @access  public
         * @return  AuthModalComponentView
         */
        showAuth: function() {
            var data = {},
                modal = ModalUtils.show('auth', data);
            return modal;
        },

        /**
         * showAuthPrompt
         * 
         * @example ModalUtils.showAuthPrompt('likes')
         * @access  public
         * @param   String authPromptKey
         * @return  AuthPromptModalComponentView
         */
        showAuthPrompt: function(authPromptKey) {
            var data = {},
                properties = AuthPromptUtils.getProperties(authPromptKey);
            data.headlines = {};
            data.headlines.primary = properties.copy.primary;
            data.headlines.secondary = properties.copy.secondary;
            data.icon = {};
            data.icon.className = properties.graphic.icon.className;
            var modal = ModalUtils.show('authPrompt', data);
            return modal;
        },

        /**
         * showBlock
         * 
         * @example ModalUtils.showBlock('primary', 'secondary')
         * @access  public
         * @param   undefined|String primary (default: 'You shall not pass...')
         * @param   undefined|String secondary (default: 'You\'ve reached a dead-end.')
         * @return  BlockModalComponentView
         */
        showBlock: function(primary, secondary) {
            var data = {};
            data.headlines = {};
            data.headlines.primary = primary || 'You shall not pass...';
            data.headlines.secondary = secondary || 'You\'ve reached a dead-end.';
            var modal = ModalUtils.show('block', data);
            return modal;
        },

        /**
         * showBlockUser
         * 
         * @access  public
         * @return  Boolean
         */
        showBlockUser: function() {
            var data = {},
                modal = ModalUtils.show('blockUser', data);
            return modal;
        },

        /**
         * showBusy
         * 
         * @access  public
         * @param   undefined|String primary (default: '')
         * @return  BusyModalComponentView
         */
        showBusy: function(primary) {
            // UserAgentUtils.freeze();
            primary = primary || '';
            var data = {};
            data.headlines = {};
            data.headlines.primary = primary;
            var modal = ModalUtils.show('busy', data);
            return modal;
        },

        /**
         * showConfirm
         * 
         * @example ModalUtils.showConfirm('Are you sure you want to delete this user?', 'This action cannot be undone.')
         * @access  public
         * @param   String primary
         * @param   String secondary
         * @param   undefined|Object buttons (default: {})
         * @return  ConfirmModalComponentView
         */
        showConfirm: function(primary, secondary, buttons) {
            buttons = buttons || {};
            buttons.yes = buttons.yes || {};
            buttons.yes.copy = buttons.yes.copy || 'Yes';
            buttons.no = buttons.no || {};
            buttons.no.copy = buttons.no.copy || 'cancel';
            var data = {};
            data.headlines = {};
            data.headlines.primary = primary;
            data.headlines.secondary = secondary;
            data.buttons = buttons;
            var modal = ModalUtils.show('confirm', data);
            return modal;
        },

        /**
         * showCrash
         * 
         * @example ModalUtils.showCrash(signature)
         * @access  public
         * @param   Object signature
         * @return  CrashModalComponentView
         */
        showCrash: function(signature) {
            var data = {};
            data.signature = signature;
            AudioUtils.play('ohho.mp3');
            var modal = ModalUtils.show('crash', data);
            return modal;
        },

        /**
         * showCreateCollection
         * 
         * @access  public
         * @return  CreateCollectionModalComponentView
         */
        showCreateCollection: function() {
            var data = {},
                modal = ModalUtils.show('createCollection', data);
            return modal;
        },

        /**
         * showCreateVectorSetDesigner
         * 
         * @access  public
         * @param   VectorSetActiveRecord vectorSet
         * @return  Promise
         */
        showCreateVectorSetDesigner: function(vectorSet) {
            ModalUtils.showBusy();
            var promise = vectorSet.read().then(function() {
                var data = {};
                data.activeRecord = vectorSet;
                ModalUtils.hideBusy();
                var modalKey = 'createVectorSetDesigner',
                    modal = ModalUtils.show(modalKey, data);
                return modal;
            });
            return promise;
        },

        /**
         * showCreateVectorSetSubset
         * 
         * @access  public
         * @param   VectorSetActiveRecord vectorSet
         * @return  Promise
         */
        showCreateVectorSetSubset: function(vectorSet) {
            ModalUtils.showBusy();
            var promise = vectorSet.read().then(function() {
                var data = {};
                data.activeRecord = vectorSet;
                ModalUtils.hideBusy();
                var modalKey = 'createVectorSetSubset',
                    modal = ModalUtils.show(modalKey, data);
                return modal;
            });
            return promise;
        },

        /**
         * showDownload
         * 
         * @example ModalUtils.showDownload('url')
         * @access  public
         * @param   String url
         * @return  DownloadModalComponentView
         */
        showDownload: function(url) {
            var data = {};
            data.headlines = {};
            data.headlines.primary = 'Download ready';
            data.headlines.secondary = 'Click below to begin your download';
            data.url = url;
            var modal = ModalUtils.show('download', data);
            return modal;
        },

        /**
         * showEdit
         * 
         * @access  public
         * @param   BaseActiveRecord activeRecord
         * @param   Boolean read (default: true)
         * @return  Promise
         */
        showEdit: function(activeRecord, read) {
            if (read === undefined) {
                read = true;
            }
            ModalUtils.showBusy();
            var delay = ConfigUtils.getPublicValue('uiux', 'formModalDelay'),
                promise = DataUtils.delay(delay).then(function() {
                    if (read === false) {
                        return activeRecord;
                    }
                    var fields = [];
                    if (activeRecord.getActiveRecordType() === 'Vector') {
                        fields.push('content');
                    }
                    return activeRecord.read(true, fields);
                }).then(function(activeRecord) {
                    var data = {};
                    data.activeRecord = activeRecord;
                    ModalUtils.hideBusy();
                    var activeRecordType = activeRecord.getActiveRecordType(),
                        modalKey = 'Edit' + (activeRecordType),
                        modal = ModalUtils.show(modalKey, data);
                    return modal;
                });
            return promise;
        },

        /**
         * showError
         * 
         * @example ModalUtils.showError('Could not download icon', 'Please try again later.')
         * @access  public
         * @param   String primary
         * @param   String secondary
         * @return  ErrorModalComponentView
         */
        showError: function(primary, secondary) {
            var data = {};
            data.headlines = {};
            data.headlines.primary = primary;
            data.headlines.secondary = secondary;
            AudioUtils.play('ohho.mp3');
            var modal = ModalUtils.show('error', data);
            __Iconduck.page.kill();
            return modal;
        },

        /**
         * showImportVector
         * 
         * @access  public
         * @param   VectorActiveRecord vector
         * @return  Boolean
         */
        showImportVector: function(vector) {
            var data = {};
            data.vector = vector;
            var modal = ModalUtils.show('importVector', data);
            return modal;
        },

        /**
         * showMailingList
         * 
         * @access  public
         * @return  Boolean
         */
        showMailingList: function() {
            var modal = ModalUtils.show('mailingList');
            return modal;
        },

        /**
         * showManageVectorSetDesigners
         * 
         * @access  public
         * @param   VectorSetActiveRecord vectorSet
         * @return  Promise
         */
        showManageVectorSetDesigners: function(vectorSet) {
            ModalUtils.showBusy();
            var promise = vectorSet.read().then(function() {
                var data = {};
                data.vectorSet = vectorSet;
                ModalUtils.hideBusy();
                var modalKey = 'manageVectorSetDesigners',
                    modal = ModalUtils.show(modalKey, data);
                return modal;
            });
            return promise;
        },

        /**
         * showManageVectorSetSubsets
         * 
         * @access  public
         * @param   VectorSetActiveRecord vectorSet
         * @return  Promise
         */
        showManageVectorSetSubsets: function(vectorSet) {
            ModalUtils.showBusy();
            var promise = vectorSet.read().then(function() {
                var data = {};
                data.vectorSet = vectorSet;
                ModalUtils.hideBusy();
                var modalKey = 'manageVectorSetSubsets',
                    modal = ModalUtils.show(modalKey, data);
                return modal;
            });
            return promise;
        },

        /**
         * showOpenWithFigma
         * 
         * @access  public
         * @param   VectorActiveRecord vector
         * @return  Promise
         */
        showOpenWithFigma: function(vector) {
            ModalUtils.showBusy();
            var promise = vector.read().then(function() {
                var data = {};
                data.vector = vector;
                ModalUtils.hideBusy();
                var modalKey = 'openWithFigma',
                    modal = ModalUtils.show(modalKey, data);
                return modal;
            });
            return promise;
        },

        /**
         * showPreview
         * 
         * @access  public
         * @param   VectorActiveRecord vector
         * @param   VectorsCollection vectorsCollection
         * @return  PreviewModalComponentView
         */
        showPreview: function(vector, vectorsCollection) {
            var title = vector.getPageTitle();
            StateUtils.replaceStateTitle(title);
            var data = {};
            data.vector = vector;
            data.vectorsCollection = vectorsCollection;
            var modal = ModalUtils.show('preview', data);
            return modal;
        },

        /**
         * showPromotion
         * 
         * @example ModalUtils.showPromotion()
         * @access  public
         * @return  PromotionModalComponentView
         */
        showPromotion: function() {
            var data = {},
                modal = ModalUtils.show('promotion', data);
            return modal;
        },

        /**
         * showQueryVectorSetVectors
         * 
         * @access  public
         * @param   VectorSetActiveRecord vectorSet
         * @return  Promise
         */
        showQueryVectorSetVectors: function(vectorSet) {
            ModalUtils.showBusy();
            var promise = vectorSet.read().then(function() {
                var data = {};
                data.vectorSet = vectorSet;
                ModalUtils.hideBusy();
                var modalKey = 'queryVectorSetVectors',
                    modal = ModalUtils.show(modalKey, data);
                return modal;
            });
            return promise;
        },

        /**
         * showSettings
         * 
         * @access  public
         * @return  SettingsModalComponentView
         */
        showSettings: function() {
            var data = {},
                modal = ModalUtils.show('settings', data);
            return modal;
        },

        /**
         * showSpotlight
         * 
         * @example ModalUtils.showSpotlight()
         * @access  public
         * @return  SpotlightModalComponentView
         */
        showSpotlight: function() {
            var data = {},
                modal = ModalUtils.show('spotlight', data);
            return modal;
        },


        /**
         * showSuccess
         * 
         * @example ModalUtils.showSuccess('You\'re all set!', 'We\'ll send you a short email when we have new icons and illustrations for you to check out.')
         * @access  public
         * @param   String primary
         * @param   String secondary
         * @return  SuccessModalComponentView
         */
        showSuccess: function(primary, secondary) {
            var data = {};
            data.headlines = {};
            data.headlines.primary = primary;
            data.headlines.secondary = secondary;
            var modal = ModalUtils.show('success', data);
            return modal;
        },

        /**
         * showUpsell
         * 
         * @example ModalUtils.showUpsell('likes')
         * @access  public
         * @param   String upsellKey
         * @return  UpsellModalComponentView
         */
        showUpsell: function(upsellKey) {
            var data = {},
                properties = UpsellUtils.getProperties(upsellKey);
            data.headlines = {};
            data.headlines.primary = properties.copy.primary;
            data.headlines.secondary = properties.copy.secondary;
            data.icon = {};
            data.icon.className = properties.graphic.icon.className;
            var modal = ModalUtils.show('upsell', data);
            return modal;
        },

        /**
         * showVectorDownloadCustomSize
         * 
         * @access  public
         * @param   VectorActiveRecord vector
         * @return  VectorDownloadCustomSizeModalComponentView
         */
        showVectorDownloadCustomSize: function(vector) {
            var data = {};
            data.vector = vector;
            var modal = ModalUtils.show('vectorDownloadCustomSize', data);
            return modal;
        },

        /**
         * unfreezeVisible
         * 
         * @access  public
         * @return  Boolean
         */
        unfreezeVisible: function() {
            var visible = ModalUtils.getVisible();
            if (visible.length === 0) {
                return false;
            }
            for (var modal of visible) {
                modal.unfreeze();
            }
            return true;
        }
    };
})();

/**
 * NativeUtils
 * 
 * @see     https://www.designcise.com/web/tutorial/whats-the-best-way-to-extend-native-javascript-objects
 * @todo    Add .hide and .show methods
 * @access  public
 * @var     Object
 */
window.NativeUtils = (function() {

    /**
     * Properties (private)
     * 
     */

    /**
     * __string
     * 
     * @access  private
     * @var     String (default: 'NativeUtils')
     */
    var __string = 'NativeUtils';

    /**
     * Methods (private)
     * 
     */

    /**
     * __extendArrays
     * 
     * @access  private
     * @return  Boolean
     */
    var __extendArrays = function() {
        __setArrayAddClass();
        __setArrayAddEventListener();
        __setArrayDisable();
        __setArrayEnable();
        __setArrayFirst();
        __setArrayLast();
        __setArrayReadonly();
        __setArrayRemoveClass();
        __setArraySetAttribute();
        return true;
    };

    /**
     * __extendHTMLElements
     * 
     * @access  private
     * @return  Boolean
     */
    var __extendHTMLElements = function() {
        __setHTMLElementAddAttributeValue();
        __setHTMLElementAddClass();
        __setHTMLElementDisable();
        __setHTMLElementEnable();
        __setHTMLElementGetView();
        __setHTMLElementReadonly();
        __setHTMLElementRemoveClass();
        return true;
    };

    /**
     * __extendNodeLists
     * 
     * @access  private
     * @return  Boolean
     */
    var __extendNodeLists = function() {
        __setNodeListAddClass();
        __setNodeListDisable();
        __setNodeListEnable();
        __setNodeListReadonly();
        __setNodeListRemoveClass();
        __setNodeListSetAttribute();
        return true;
    };

    /**
     * __extendNumbers
     * 
     * @access  private
     * @return  Boolean
     */
    var __extendNumbers = function() {
        __setNumberToInt();
        return true;
    };

    /**
     * __extendStrings
     * 
     * @access  private
     * @return  Boolean
     */
    var __extendStrings = function() {
        __setStringToInt();
        return true;
    };

    /**
     * __setArrayAddClass
     * 
     * @access  private
     * @return  Boolean
     */
    var __setArrayAddClass = function() {
        var response = __setNativeObjectProperty(Array, 'addClass', function(className) {
            for (var entry of this) {
                if (entry instanceof HTMLElement === false) {
                    continue;
                }
                entry.addClass(className);
            }
            return this;
        });
        return response;
    };

    /**
     * __setArrayAddEventListener
     * 
     * @access  private
     * @return  Boolean
     */
    var __setArrayAddEventListener = function() {
        var response = __setNativeObjectProperty(Array, 'addEventListener', function(eventName, handle) {
            for (var entry of this) {
                if (entry instanceof HTMLElement === false) {
                    continue;
                }
                entry.addEventListener(eventName, handle);
            }
            return this;
        });
        return response;
    };

    /**
     * __setArrayDisable
     * 
     * @access  private
     * @return  Boolean
     */
    var __setArrayDisable = function() {
        var response = __setNativeObjectProperty(Array, 'disable', function() {
            for (var entry of this) {
                if (entry instanceof HTMLElement === false) {
                    continue;
                }
                entry.disable();
            }
            return this;
        });
        return response;
    };

    /**
     * __setArrayEnable
     * 
     * @access  private
     * @return  Boolean
     */
    var __setArrayEnable = function() {
        var response = __setNativeObjectProperty(Array, 'enable', function() {
            for (var entry of this) {
                if (entry instanceof HTMLElement === false) {
                    continue;
                }
                entry.enable();
            }
            return this;
        });
        return response;
    };

    /**
     * __setArrayFirst
     * 
     * @access  private
     * @return  Boolean
     */
    var __setArrayFirst = function() {
        var response = __setNativeObjectProperty(Array, 'first', function() {
            var length = this.length;
            if (length === 0) {
                return null;
            }
            var entry = this[0];
            return entry;
        });
        return response;
    };

    /**
     * __setArrayLast
     * 
     * @access  private
     * @return  Boolean
     */
    var __setArrayLast = function() {
        var response = __setNativeObjectProperty(Array, 'last', function() {
            var length = this.length;
            if (length === 0) {
                return null;
            }
            var entry = this[length - 1];
            return entry;
        });
        return response;
    };

    /**
     * __setArrayReadonly
     * 
     * @access  private
     * @return  Boolean
     */
    var __setArrayReadonly = function() {
        var response = __setNativeObjectProperty(Array, 'readonly', function(readonly) {
            for (var entry of this) {
                if (entry instanceof HTMLElement === false) {
                    continue;
                }
                entry.readonly(readonly);
            }
            return this;
        });
        return response;
    };

    /**
     * __setArrayRemoveClass
     * 
     * @access  private
     * @return  Boolean
     */
    var __setArrayRemoveClass = function() {
        var response = __setNativeObjectProperty(Array, 'removeClass', function(className) {
            for (var entry of this) {
                if (entry instanceof HTMLElement === false) {
                    continue;
                }
                entry.removeClass(className);
            }
            return this;
        });
        return response;
    };

    /**
     * __setArraySetAttribute
     * 
     * @access  private
     * @return  Boolean
     */
    var __setArraySetAttribute = function() {
        var response = __setNativeObjectProperty(Array, 'setAttribute', function(attributeKey, attributeValue) {
            for (var entry of this) {
                if (entry instanceof HTMLElement === false) {
                    continue;
                }
                entry.setAttribute(attributeKey, attributeValue);
            }
            return this;
        });
        return response;
    };

    /**
     * __setHTMLElementAddAttributeValue
     * 
     * @access  private
     * @return  Boolean
     */
    var __setHTMLElementAddAttributeValue = function() {
        var response = __setNativeObjectProperty(HTMLElement, 'addAttributeValue', function(attributeKey, attributeValue) {
            var currentAttributeValue = this.getAttribute(attributeKey),
                newAttributeValue = (currentAttributeValue) + ' ' + (attributeValue);
            this.setAttribute(attributeKey, newAttributeValue);
            return this;
        });
        return response;
    };

    /**
     * __setHTMLElementAddClass
     * 
     * @access  private
     * @return  Boolean
     */
    var __setHTMLElementAddClass = function() {
        var response = __setNativeObjectProperty(HTMLElement, 'addClass', function(className) {
            this.classList.add(className);
            return this;
        });
        return response;
    };

    /**
     * __setHTMLElementDisable
     * 
     * @access  private
     * @return  Boolean
     */
    var __setHTMLElementDisable = function() {
        var response = __setNativeObjectProperty(HTMLElement, 'disable', function() {
            this.setAttribute('disabled', '');
            return this;
        });
        return response;
    };

    /**
     * __setHTMLElementEnable
     * 
     * @access  private
     * @return  Boolean
     */
    var __setHTMLElementEnable = function() {
        var response = __setNativeObjectProperty(HTMLElement, 'enable', function() {
            this.removeAttribute('disabled');
            return this;
        });
        return response;
    };

    /**
     * __setHTMLElementGetView
     * 
     * @access  private
     * @return  Boolean
     */
    var __setHTMLElementGetView = function() {
        var response = __setNativeObjectProperty(HTMLElement, 'getView', function() {
            var view = this.data.view || null;
            return view;
        });
        return response;
    };

    /**
     * __setHTMLElementReadonly
     * 
     * @access  private
     * @return  Boolean
     */
    var __setHTMLElementReadonly = function() {
        var response = __setNativeObjectProperty(HTMLElement, 'readonly', function(readonly) {
            if (readonly === true) {
                this.setAttribute('readonly', '');
                return this;
            }
            this.removeAttribute('readonly');
            return this;
        });
        return response;
    };

    /**
     * __setHTMLElementRemoveClass
     * 
     * @access  private
     * @return  Boolean
     */
    var __setHTMLElementRemoveClass = function() {
        var response = __setNativeObjectProperty(HTMLElement, 'removeClass', function(className) {
            this.classList.remove(className);
            return this;
        });
        return response;
    };

    /**
     * __setNativeObjectProperty
     * 
     * @access  private
     * @param   Object reference
     * @param   String methodName
     * @param   Function fn
     * @return  Boolean
     */
    var __setNativeObjectProperty = function(reference, methodName, fn) {
        if (reference.prototype.hasOwnProperty(methodName) === true) {
            return false;
        }
        Object.defineProperty(reference.prototype, methodName, {
            writable: false,
            enumerable: false,
            configurable: false,
            value: function() {
                var args = Array.prototype.slice.call(arguments),
                    response = fn.apply(this, args);
                return response;
            }
        });
        return true;
    };

    /**
     * __setNodeListAddClass
     * 
     * @access  private
     * @return  Boolean
     */
    var __setNodeListAddClass = function() {
        var response = __setNativeObjectProperty(NodeList, 'addClass', function(className) {
            for (var $element of this) {
                $element.addClass(className);
            }
            return this;
        });
        return response;
    };

    /**
     * __setNodeListDisable
     * 
     * @access  private
     * @return  Boolean
     */
    var __setNodeListDisable = function() {
        var response = __setNativeObjectProperty(NodeList, 'disable', function() {
            for (var $element of this) {
                $element.disable();
            }
            return this;
        });
        return response;
    };

    /**
     * __setNodeListEnable
     * 
     * @access  private
     * @return  Boolean
     */
    var __setNodeListEnable = function() {
        var response = __setNativeObjectProperty(NodeList, 'enable', function() {
            for (var $element of this) {
                $element.enable();
            }
            return this;
        });
        return response;
    };

    /**
     * __setNodeListReadonly
     * 
     * @access  private
     * @return  Boolean
     */
    var __setNodeListReadonly = function() {
        var response = __setNativeObjectProperty(NodeList, 'readonly', function(readonly) {
            for (var $element of this) {
                $element.readonly(readonly);
            }
            return this;
        });
        return response;
    };

    /**
     * __setNodeListRemoveClass
     * 
     * @access  private
     * @return  Boolean
     */
    var __setNodeListRemoveClass = function() {
        var response = __setNativeObjectProperty(NodeList, 'removeClass', function(className) {
            for (var $element of this) {
                $element.removeClass(className);
            }
            return this;
        });
        return response;
    };

    /**
     * __setNodeListSetAttribute
     * 
     * @access  private
     * @return  Boolean
     */
    var __setNodeListSetAttribute = function() {
        var response = __setNativeObjectProperty(NodeList, 'setAttribute', function(attributeKey, attributeValue) {
            for (var $element of this) {
                $element.setAttribute(className);
            }
            return this;
        });
        return response;
    };

    /**
     * __setNumberToInt
     * 
     * @access  private
     * @return  Boolean
     */
    var __setNumberToInt = function() {
        var response = __setNativeObjectProperty(Number, 'toInt', function() {
            var value = parseInt(this, 10);
            return value;
        });
        return response;
    };

    /**
     * __setStringToInt
     * 
     * @access  private
     * @return  Boolean
     */
    var __setStringToInt = function() {
        var response = __setNativeObjectProperty(String, 'toInt', function() {
            var value = parseInt(this, 10);
            return value;
        });
        return response;
    };

    /**
     * Methods (public)
     * 
     */
    return {

        /**
         * init
         * 
         * @access  public
         * @return  Boolean
         */
        init: function() {
            __extendArrays();
            __extendHTMLElements();
            __extendNodeLists();
            __extendNumbers();
            __extendStrings();
            return true;
        }
    };
})();

/**
 * NotificationUtils
 * 
 * @access  public
 * @var     Object
 */
window.NotificationUtils = (function() {

    /**
     * Properties (private)
     * 
     */

    /**
     * __currentGrowl
     * 
     * @access  private
     * @var     null|GrowlNotificationComponentView (default: null)
     */
    var __currentGrowl = null;

    /**
     * __string
     * 
     * @access  private
     * @var     String (default: 'NotificationUtils')
     */
    var __string = 'NotificationUtils';

    /**
     * Methods (private)
     * 
     */

    /**
     * __drawGrowlNotification
     * 
     * @access  private
     * @param   String msg
     * @return  HTMLElement
     */
    var __drawGrowlNotification = function(msg) {
        var data = {};
        data.msg = msg;
        var templateName = 'GrowlNotificationComponent',
            $element = ElementUtils.renderTemplate(templateName, data),
            $parent = document.body;
        $parent.appendChild($element);
        return $element;
    };

    /**
     * __setupGrowlNotification
     * 
     * @access  private
     * @param   String msg
     * @return  GrowlNotificationComponentView
     */
    var __setupGrowlNotification = function(msg) {
        NotificationUtils.hideCurrentGrowl();
        var $element = __drawGrowlNotification(msg),
            view = $element.getView();
        __currentGrowl = view;
        return view;
    };

    /**
     * Methods (public)
     * 
     */
    return {

        /**
         * hideCurrentGrowl
         * 
         * @access  public
         * @return  Boolean
         */
        hideCurrentGrowl: function() {
            var currentGrowl = __currentGrowl;
            if (currentGrowl === null) {
                return false;
            }
            currentGrowl.hide();
            return true;
        },

        /**
         * showDismissGrowl
         * 
         * @access  public
         * @param   String msg
         * @return  Boolean
         */
        showDismissGrowl: function(msg) {
            var view = __setupGrowlNotification(msg);
            view.setAction('dismiss');
            view.setTimeout(5500);
            view.show();
            return true;
        },

        /**
         * showFirstLikeGrowl
         * 
         * @access  public
         * @return  Boolean
         */
        showFirstLikeGrowl: function() {
            var user = AuthUtils.getUser();
            if (user.getLikes().getCollectionItems().length() === 1) {
                var msg = 'You just liked your first thing on Iconduck. You can find liked icons and sets on the Likes page.',
                    view = __setupGrowlNotification(msg);
                view.setAction('viewLikesPage');
                view.setTimeout(5500);
                view.show();
                return true;
            }
            return false;
        },

        /**
         * showReloadGrowl
         * 
         * @access  public
         * @param   String destination
         * @return  Boolean
         */
        showReloadGrowl: function(destination) {
            var msg = 'Please reload the page to see the most recent version:',
                view = __setupGrowlNotification(msg),
                properties = {};
            properties.destination = destination;
            view.setActionProperties('reload', properties);
            view.setAction('reload');
            view.setTimeout(5500);
            view.show();
            return true;
        },

        /**
         * showSimpleGrowl
         * 
         * @access  public
         * @param   String msg
         * @param   undefined|Number timeout
         * @return  Boolean
         */
        showSimpleGrowl: function(msg, timeout) {
            var view = __setupGrowlNotification(msg);
            view.setAction('simple');
            timeout = timeout || 4500;
            view.setTimeout(timeout);
            view.show();
            return true;
        }
    };
})();

/**
 * RequestUtils
 * 
 * @access  public
 * @var     Object
 */
window.RequestUtils = (function() {

    /**
     * Properties (private)
     * 
     */

    /**
     * __string
     * 
     * @access  private
     * @var     String (default: 'RequestUtils')
     */
    var __string = 'RequestUtils';

    /**
     * Methods (private)
     * 
     */

    /**
     * __crash
     * 
     * @access  private
     * @param   String msg
     * @param   Object requestOptions
     * @return  Boolean
     */
    var __crash = function(msg, requestOptions) {
        if (requestOptions.showCrashModal === false) {
            return false;
        }
        ModalUtils.closeVisible();
        var modal = ModalUtils.showCrash({"basename":"Request.js","line":41});
        modal.sendCrashReport();
        __Iconduck.page.kill();
        return true;
    };

    /**
     * __getFormData
     * 
     * @access  private
     * @param   Object data
     * @return  FormData
     */
    var __getFormData = function(data) {
        var formData = new FormData();
        for (var key in data) {
            var value = data[key];
            key = 'data[' + (key) + ']';
            formData.append(key, value);
        }
        return formData;
    };

    /**
     * __handleXHRRequestResponse
     * 
     * @access  private
     * @param   Object xhr
     * @param   Function resolve
     * @param   Function reject
     * @param   Object options
     * @return  Boolean
     */
    var __handleXHRRequestResponse = function(xhr, resolve, reject, options) {
        var valid = __validateXHRRequestResponse(xhr, options);
        if (valid === false) {
            return false;
        }
        var resolved = __resolveXHRRequest(xhr, resolve, reject, options);
        return resolved;
    };

    /**
     * __resolveXHRRequest
     * 
     * @access  private
     * @param   Object xhr
     * @param   Function resolve
     * @param   Function reject
     * @param   Object options
     * @return  Boolean
     */
    var __resolveXHRRequest = function(xhr, resolve, reject, options) {
        var response = xhr.response;
        response = JSON.parse(response);
        if (response.errors !== null) {
            if (response.errors[0].code === 'svRj0') {
                window.location.reload();
                return false;
            }
            reject(response);
            return false;
        }
        if (response.data === null) {
            var msg = 'Processing: data: null';
            __crash(msg, options);
            return false;
        }
        if (response.data.success === false) {
            var msg = 'Processing: success: false'
            __crash(msg, options);
            return false;
        }
        resolve(response);
        return true;
    };

    /**
     * __setXHRContentTypeHeaders
     * 
     * @access  private
     * @param   Object xhr
     * @return  Boolean
     */
    var __setXHRContentTypeHeaders = function(xhr) {
        xhr.setRequestHeader('Content-Type', 'application/x-www-form-urlencoded');
        return true;
    };

    /**
     * __validateXHRRequestResponse
     * 
     * @access  private
     * @param   Object xhr
     * @param   Object options
     * @return  Boolean
     */
    var __validateXHRRequestResponse = function(xhr, options) {

        // < 200 error code
        if (xhr.status < 200) {
            var msg = 'Processing: status code: < 200 (' + (xhr.status) + ')'
            __crash(msg, options);
            return false;
        }

        // > 400 error code (eg. 404, server error, etc)
        if (xhr.status >= 400) {
            var msg = 'Processing: status code: >= 400 (' + (xhr.status) + ')';
            __crash(msg, options);
            return false;
        }

        // Invalid JSON
        var response = xhr.response;
        try {
            response = JSON.parse(response);
        } catch (err) {
            var msg = 'Invalid JSON'
            __crash(msg, options);
            return false;
        }
        return true;
    };

    /**
     * Methods (public)
     * 
     */
    return {

        /**
         * delete
         * 
         * @access  public
         * @param   String path
         * @param   undefined|Object data (default: {})
         * @param   undefined|Object options (default: {})
         * @return  Promise
         */
        delete: function(path, data, options) {
            var method = 'DELETE',
                promise = RequestUtils.request(path, method, data, options);
            return promise;
        },

        /**
         * get
         * 
         * @access  public
         * @param   String path
         * @param   undefined|Object data (default: {})
         * @param   undefined|Object options (default: {})
         * @return  Promise
         */
        get: function(path, data, options) {
            var method = 'GET',
                promise = RequestUtils.request(path, method, data, options);
            return promise;
        },

        /**
         * getURLParamValue
         * 
         * @see     https://www.sitepoint.com/get-url-parameters-with-javascript/
         * @see     https://developer.mozilla.org/en-US/docs/Web/API/URLSearchParams/get
         * @access  public
         * @param   String name
         * @return  null|mixed
         */
        getURLParamValue: function(name) {
            var queryString = window.location.search,
                urlParams = new URLSearchParams(queryString),
                value = urlParams.get(name)
            return value;
        },

        /**
         * loadImage
         * 
         * @access  public
         * @param   String src
         * @return  Promise
         */
        loadImage: function(src) {
            var promise = new Promise(function(resolve, reject) {
                var image = new Image();
                image.onerror = function() {
                    reject(this);
                };
                image.onload = function() {
                    resolve(this);
                };
                image.src = src;
            });
            return promise;
        },

        /**
         * patch
         * 
         * @access  public
         * @param   String path
         * @param   undefined|Object data (default: {})
         * @param   undefined|Object options (default: {})
         * @return  Promise
         */
        patch: function(path, data, options) {
            var method = 'PATCH',
                promise = RequestUtils.request(path, method, data, options);
            return promise;
        },

        /**
         * post
         * 
         * @access  public
         * @param   String path
         * @param   undefined|Object data (default: {})
         * @param   undefined|Object options (default: {})
         * @return  Promise
         */
        post: function(path, data, options) {
            var method = 'POST',
                promise = RequestUtils.request(path, method, data, options);
            return promise;
        },

        /**
         * request
         * 
         * @see     https://developer.mozilla.org/en-US/docs/Web/API/Request/Request
         * @access  public
         * @param   String path
         * @param   undefined|String method (default: 'get')
         * @param   undefined|Object data (default: {})
         * @param   undefined|Object options (default: {})
         * @return  Promise
         */
        request: function(path, method, data, options) {

            // Normalization
            method = method || 'get';
            method = method.toUpperCase();
            data = data || {};
            options = options || {};

            // Fields check
            if (data.fields !== undefined) {
                data.fields = data.fields.join(',');
            }

            // Data
            var formData = options.formData || __getFormData(data),
                url = ConfigUtils.getAPIEndpoint(path);
            if (method === 'GET') {
                formData = data;
            }

            // Request
            var promise = new Promise(function(resolve, reject) {
                var xhr = new XMLHttpRequest(),
                    queryString = new URLSearchParams(formData).toString();
                queryString = queryString.trim();
                if (method === 'GET' && queryString !== '') {
                    url = (url) + '?' + (queryString);
                }
                xhr.open(method, url);
                __setXHRContentTypeHeaders(xhr);
                xhr.onload = __handleXHRRequestResponse.bind(window, xhr, resolve, reject, options);
                xhr.send(queryString);
            });
            return promise;
        },

        /**
         * submit
         * 
         * @see     https://stackoverflow.com/questions/133925/javascript-post-request-like-a-form-submit
         * @access  public
         * @param   String destination
         * @param   String method
         * @param   undefined|Object data (default: {})
         * @return  Promise
         */
        submit: function(destination, method, data) {
            data = data || {};
            var $form = document.createElement('form');
            $form.method = method;
            $form.action = destination;
            for (const key in data) {
                if (data.hasOwnProperty(key) === true) {
                    var $hidden = document.createElement('input');
                    $hidden.type = 'hidden';
                    $hidden.name = key;
                    $hidden.value = data[key];
                    $form.appendChild($hidden);
                }
            }
            document.body.appendChild($form);
            $form.submit();
            var promise = DataUtils.getPromise(true);
            return promise;
        }
    };
})();

/**
 * SpotlightUtils
 * 
 * @abstract
 */
window.SpotlightUtils = (function() {

    /**
     * Methods (private)
     * 
     */

    /**
     * __getVectorSetResults
     * 
     * @access  private
     * @return  Array
     */
    var __getVectorSetResults = function() {
        var results = [],
            vectorSets = __Iconduck.page.getVectorSets().all();
        for (var vectorSet of vectorSets) {
            results.push({
                label: vectorSet.getName(),
                destination: vectorSet.getPath(),
                iconKey: 'collection'
            });
        }
        return results;
    };

    /**
     * Properties (private)
     * 
     */

    /**
     * __string
     * 
     * @access  private
     * @var     String (default: 'SpotlightUtils')
     */
    var __string = 'SpotlightUtils';

    /**
     * Methods (public)
     * 
     */
    return {

        /**
         * getDefaultStateResults
         * 
         * @access  public
         * @return  Array
         */
        getDefaultStateResults: function() {
            var results = [];
            results.push({
                label: 'Home',
                destination: '/',
                iconKey:'home'
            });
            if (AuthUtils.getUser() === null) {
                results.push({
                    label: 'Login',
                    destination: '/login',
                    iconKey:'key'
                });
                results.push({
                    label: 'Sign up',
                    destination: '/signup',
                    iconKey:'user-add'
                });
            } else {
                results.push({
                    label: 'Likes',
                    destination: '/likes',
                    iconKey:'heart'
                });
                results.push({
                    label: 'Collections',
                    destination: '/collections',
                    iconKey:'folder-open'
                });
            }
            results.push({
                label: 'Changelog',
                destination: '/changelog',
                iconKey:'link'
            });
            results.push({
                label: 'Figma Plugin',
                destination: 'https://www.figma.com/community/plugin/1074084347757622122',
                iconKey:'logo-figma'
            });
            results.push({
                label: 'Canva App',
                destination: 'https://www.canva.com/apps/AAE4vlau17g-iconduck',
                iconKey:'logo-canva'
            });
            results.push({
                label: 'Google Add-on',
                destination: 'https://workspace.google.com/marketplace/app/iconduck/300502618303',
                iconKey:'link'
            });
            return results;
        },

        /**
         * getIndexStateResults
         * 
         * @access  public
         * @return  Array
         */
        getIndexStateResults: function() {
            var results = this.getDefaultStateResults(),
                vectorSetResults = __getVectorSetResults();
            if (AuthUtils.admin() === true) {
                results.push({
                    label: 'Admin',
                    destination: '/admin',
                    iconKey:'lock'
                });
                results.push({
                    label: 'Admin / Applications',
                    destination: '/admin/applications',
                    iconKey:'lock'
                });
                results.push({
                    label: 'Admin / Collections',
                    destination: '/admin/collections',
                    iconKey:'lock'
                });
                results.push({
                    label: 'Admin / Designers',
                    destination: '/admin/designers',
                    iconKey:'lock'
                });
                results.push({
                    label: 'Admin / Figma Plugins',
                    destination: '/admin/figmaPlugins',
                    iconKey:'lock'
                });
                results.push({
                    label: 'Admin / Licenses',
                    destination: '/admin/licenses',
                    iconKey:'lock'
                });
                results.push({
                    label: 'Admin / Redirects',
                    destination: '/admin/redirects',
                    iconKey:'lock'
                });
                results.push({
                    label: 'Admin / Subsets',
                    destination: '/admin/subsets',
                    iconKey:'lock'
                });
                results.push({
                    label: 'Admin / Upgrades',
                    destination: '/admin/upgrades',
                    iconKey:'lock'
                });
                results.push({
                    label: 'Admin / User Email Templates',
                    destination: '/admin/userEmailTemplates',
                    iconKey:'lock'
                });
                results.push({
                    label: 'Admin / Users',
                    destination: '/admin/users',
                    iconKey:'lock'
                });
                results.push({
                    label: 'Admin / Vector Sets',
                    destination: '/admin/vectorSets',
                    iconKey:'lock'
                });
                results.push({
                    label: 'Admin / Vendors',
                    destination: '/admin/vendors',
                    iconKey:'lock'
                });

                // Docs
                results.push({
                    label: 'Google Analytics',
                    destination: 'https://analytics.google.com/analytics/web/#/p259744113/reports/reportinghub',
                    iconKey: 'lock'
                });
                results.push({
                    label: 'Google Search Console',
                    destination: 'https://search.google.com/search-console/performance/search-analytics?resource_id=sc-domain%3Aiconduck.com&num_of_months=6',
                    iconKey: 'lock'
                });
                results.push({
                    label: 'Plausible',
                    destination: 'https://plausible.io/iconduck.com',
                    iconKey: 'lock'
                });
                results.push({
                    label: 'Figma',
                    destination: 'https://www.figma.com/files/team/1073685045520582497/Iconduck',
                    iconKey: 'lock'
                });
                results.push({
                    label: 'Cloudinary',
                    destination: 'https://console.cloudinary.com/console/c-a77b46e15d6c484ff8dfac800abac9',
                    iconKey: 'lock'
                });
                results.push({
                    label: 'Linear',
                    destination: 'https://linear.app/iconduck/team/PRD/all',
                    iconKey: 'lock'
                });
                results.push({
                    label: 'Gumroad',
                    destination: 'https://app.gumroad.com/dashboard/sales',
                    iconKey: 'lock'
                });
                results.push({
                    label: 'Postmark',
                    destination: 'https://account.postmarkapp.com/servers/8313187/streams',
                    iconKey: 'lock'
                });
            }
            results = results.concat(vectorSetResults);
            return results;
        }
    };
})();

/**
 * StateUtils
 * 
 * @access  public
 * @var     Object
 */
window.StateUtils = (function() {

    /**
     * Properties (private)
     * 
     */

    /**
     * __initialState
     * 
     * @access  private
     * @var     null|Object (default: null)
     */
    // var __initialState = null;

    /**
     * __states
     * 
     * @access  private
     * @var     Array (default: [])
     */
    var __states = [];

    /**
     * __store
     * 
     * @access  private
     * @var     Object (default: {})
     */
    var __store = {};

    /**
     * __string
     * 
     * @access  private
     * @var     String (default: 'StateUtils')
     */
    var __string = 'StateUtils';

    /**
     * Methods (private)
     * 
     */

    /**
     * __getInitialStatePath
     * 
     * @access  private
     * @return  String
     */
    var __getInitialStatePath = function() {
        var path = window.location.href,
            host = window.location.host;
        path = path.replace('https://', '');
        path = path.replace(host, '');
        return path;
    };

    /**
     * _handlePopStateEvent
     * 
     * @access  private
     * @param   PopStateEvent event
     * @return  Boolean
     */
    var __handlePopStateEvent = function(event) {

        // Bail if app is dead
        if (__Iconduck.page.dead() === true) {
            return false;
        }

        // Hide modals; get state properties; if no state, assume it's the first
        ModalUtils.closeVisible();
        var state = event.state || __states.first(),
            type = state.type;
// console.log(state);
        // If user is navigating back to initial state
        if (type === 'initial') {
            var initialState = __states.first();
// console.log(initialState.path, __getInitialStatePath());
            if (initialState.path === __getInitialStatePath()) {
                document.title = state.title;
                return true;
            }
            window.location.reload();
            return false;
        }

        // Vector thumb is not on page
        if (type === 'PreviewModalComponentView') {
            // console.log(state);
        }
        var $body = document.querySelector('body'),
            path = state.path,
            path = path.replace(/\?.+$/, ''),
            selector = '[href="' + (path) + '"]',
            $anchor = $body.querySelector(selector);
// console.log(selector);
        if ($anchor === null) {
            window.location.reload();
            return false;
        }

        // Vector thumb is on page, but was not the... (?)
        var initialState = __states.first();
        if (state.path === initialState.path) {
            document.title = state.title;
            return true;
        }

        // Show preview modal
        document.title = state.title;
        var vectorBlock = $anchor.getView();
        vectorBlock.showPreviewModal();
        return true;
    };

    /**
     * Methods (public)
     * 
     */
    return {

        /**
         * addPopStateEventListener
         * 
         * @see     https://developer.mozilla.org/en-US/docs/Web/API/Window/popstate_event#the_history_stack
         * @access  public
         * @return  Boolean
         */
        addPopStateEventListener: function() {
            if (UserAgentUtils.supports.history() === false) {
                return false;
            }
            var handler = __handlePopStateEvent;
            setTimeout(function() {
                window.addEventListener('popstate', handler);
            }, 0);
            return true;
        },

        /**
         * pushInitialState
         * 
         * The name for this method can be a bit confusing (but I couldn't come
         * up with a better one): it doesn't "push" the initial state upon page
         * load. Rather, it will push a new state that is a copy of the original
         * one. This is to handle an experience like a user previewing an icon
         * and then leaving that modal. There should then be a new state in
         * their history that matches the initial page load.
         * 
         * @access  public
         * @return  Boolean
         */
        pushInitialState: function() {
            if (UserAgentUtils.supports.history() === false) {
                return false;
            }
            var state = __states.first(),
                path = state.path,
                type = state.type,
                title = state.title,
                response = StateUtils.pushState(path, type, title);
            return response;
        },

        /**
         * pushState
         * 
         * @see     https://developer.mozilla.org/en-US/docs/Web/API/History/pushState
         * @access  public
         * @param   String path
         * @param   String type
         * @param   String title (default: '')
         * @param   undefined|Object data (default: {})
         * @return  Boolean
         */
        pushState: function(path, type, title, data) {
            if (UserAgentUtils.supports.history() === false) {
                return false;
            }
            data = data || {};
            var state = {},
                path = path;
            state.path = path;
            state.title = title || document.title;
            state.type = type;
            state.data = data;
            __states.push(state);
            window.history.pushState(state, '', path);
            document.title = state.title;
            return true;
        },

        /**
         * replaceStateTitle
         * 
         * @see     https://developer.mozilla.org/en-US/docs/Web/API/History/replaceState
         * @access  public
         * @param   String title
         * @return  Boolean
         */
        replaceStateTitle: function(title) {
// console.log('ahhh');
            if (UserAgentUtils.supports.history() === false) {
                return false;
            }
            var state = window.history.state;
            state.title = title;
            var url = state.path;
            window.history.replaceState(state, '', url);
            document.title = title;
            return true;
        },

        /**
         * states
         * 
         * @access  public
         * @return  Array
         */
        states: function() {
            var states = __states;
            return states;
        },

        /**
         * trackInitialState
         * 
         * @access  public
         * @return  Boolean
         */
        trackInitialState: function() {
// console.log('wtf');
            var state = {},
                path = __getInitialStatePath();
            state.path = path;
            state.title = document.title;
            state.type = 'initial';
            __states.push(state);
            return true;
        }
    };
})();

/**
 * UpsellUtils
 * 
 * @abstract
 */
window.UpsellUtils = (function() {

    /**
     * Properties (private)
     * 
     */

    /**
     * __properties
     * 
     * @access  private
     * @var     Object
     */
    var __properties = {
        collectionDownloads: {
            copy: {
                primary: 'Please upgrade to download collections',
                secondary: 'This is a **one-time fee** of **$29**, and after you\'ve upgraded you can download unlimited collections.'
            },
            graphic: {
                icon: {
                    className: 'icon-crown pulse once short small'
                }
            }
        },
        largeSizes: {
            copy: {
                primary: 'Please upgrade to download large icons',
                secondary: 'This is a **one-time fee** of **$29**, and after you\'ve upgraded you can download unlimited icons at any size.'
            },
            graphic: {
                icon: {
                    className: 'icon-crown pulse once short small'
                }
            }
        },
        maxDownloadCount: {
            copy: {
                primary: 'You\'ve downloaded<br />**100** icons!',
                secondary: 'To download **unlimited** icons, you will need to upgrade for a<br />**one-time fee** of **$29**.'
            },
            graphic: {
                icon: {
                    className: 'icon-crown pulse once short small'
                }
            }
        },
        zips: {
            copy: {
                primary: 'Please upgrade to download ZIP files',
                secondary: 'This is a **one-time fee** of **$29**, and after you\'ve upgraded you can download unlimited ZIP files.'
            },
            graphic: {
                icon: {
                    className: 'icon-crown pulse once short small'
                }
            }
        }
    };

    /**
     * __string
     * 
     * @access  private
     * @var     String (default: 'UpsellUtils')
     */
    var __string = 'UpsellUtils';

    /**
     * Methods (private)
     * 
     */

    /**
     * __getCopy
     * 
     * @access  private
     * @param   String upsellKey
     * @return  Object
     */
    var __getCopy = function(upsellKey) {
        var copy = {},
            primary = __properties[upsellKey].copy.primary,
            secondary = __properties[upsellKey].copy.secondary;
        primary = primary.replace(/\*\*([^\*]+)\*\*/g, '<strong>$1</strong>');
        secondary = secondary.replace(/\*\*([^\*]+)\*\*/g, '<strong>$1</strong>');
        copy.primary = primary;
        copy.secondary = secondary;
        return copy;
    };

    /**
     * __getProperties
     * 
     * @access  private
     * @param   String upsellKey
     * @return  Object
     */
    var __getProperties = function(upsellKey) {
        var properties = {};
        properties.copy = __getCopy(upsellKey);
        properties.graphic = __properties[upsellKey].graphic;
        return properties;
    };

    /**
     * Methods (public)
     * 
     */
    return {

        /**
         * getProperties
         * 
         * @access  public
         * @param   String upsellKey
         * @return  Boolean
         */
        getProperties: function(upsellKey) {
            var properties = __getProperties(upsellKey);
            return properties;
        }
    };
})();

/**
 * UserAgentUtils
 * 
 * @access  public
 * @var     Object
 */
window.UserAgentUtils = (function() {

    /**
     * Properties (private)
     * 
     */

    /**
     * __focused
     * 
     * @access  private
     * @var     Boolean (default: true)
     */
    var __focused = true;

    /**
     * __frozen
     * 
     * @access  private
     * @var     Boolean (default: false)
     */
    // var __frozen = false;

    /**
     * __frozenHandler
     * 
     * @access  private
     * @var     null|Function (default: null)
     */
    var __frozenHandler = null;

    /**
     * __string
     * 
     * @access  private
     * @var     String (default: 'UserAgentUtils')
     */
    var __string = 'UserAgentUtils';

    /**
     * Methods (private)
     * 
     */

    /**
     * __addFreezeKeydownEvent
     * 
     * @access  private
     * @return  void
     */
    // var __addFreezeKeydownEvent = function() {
    //     var $element = document,
    //         handler = __handleFreezeKeydownEvent.bind(UserAgentUtils);
    //     __frozenHandler = handler;
    //     $element.addEventListener('keydown', handler, true);
    // };

    /**
     * __handleFreezeKeydownEvent
     * 
     * @access  private
     * @param   Object event
     * @return  void
     */
    // var __handleFreezeKeydownEvent = function(event) {
    //     event.preventDefault();
    //     event.stopPropagation();
    // };

    /**
     * __removeFreezeKeydownEvent
     * 
     * @access  private
     * @return  void
     */
    // var __removeFreezeKeydownEvent = function() {
    //     var $element = document,
    //         handler = __frozenHandler;
    //     $element.removeEventListener('keydown', handler, true);
    // };

    /**
     * Methods (public)
     * 
     */
    return {

        /**
         * init
         * 
         * @see     https://stackoverflow.com/questions/7389328/detect-if-browser-tab-has-focus
         * @access  public
         * @return  Boolean
         */
        init: function() {
            window.onfocus = function() {
                __focused = true;
            };
            window.onblur = function() {
                __focused = false;
            };
            return true;
        },

        /**
         * alert
         * 
         * @access  public
         * @param   String primary
         * @param   String secondary
         * @return  Promise
         */
        alert: function(primary, secondary) {
            var promise = new Promise(function(resolve, reject) {
                ModalUtils.showAlert(primary, secondary);
                resolve(alert);
            });
            return promise;
        },

        /**
         * confirm
         * 
         * @access  public
         * @param   String primary
         * @param   String secondary
         * @return  Promise
         */
        confirm: function(primary, secondary) {
            var promise = new Promise(function(resolve, reject) {
                var confirmModal = ModalUtils.showConfirm(primary, secondary);
                confirmModal.addCustomEventListener('yes', function() {
                    resolve();
                });
            });
            return promise;
        },

        /**
         * copyToClipboard
         * 
         * @access  public
         * @param   String content
         * @return  void
         */
        copyToClipboard: function(content) {
            var $input = document.createElement('input');
            $input.type = 'text';
            $input.value = content;
            document.body.appendChild($input);
            $input.select();
            document.execCommand('Copy');
            document.body.removeChild($input);
        },

        /**
         * focused
         * 
         * @access  public
         * @return  Boolean
         */
        focused: function() {
            var focused = __focused;
            return focused;
        },

        /**
         * freeze
         * 
         * @access  public
         * @return  Boolean
         */
        // freeze: function() {
        //     if (__frozen === true) {
        //         return false;
        //     }
        //     __addFreezeKeydownEvent();
        //     __frozen = true;
        //     var $body = document.body;
        //     $body.classList.add('frozen');
        //     return true;
        // },

        /**
         * frozen
         * 
         * @access  public
         * @return  Boolean
         */
        // frozen: function() {
        //     var frozen = __frozen;
        //     return frozen;
        // },

        /**
         * not
         * 
         * @access  public
         * @var     Object
         */
        not: {

            /**
             * touch
             * 
             * @access  public
             * @return  Boolean
             */
            touch: function() {
                var touch = UserAgentUtils.supports.touch();
                if (touch === true) {
                    return false;
                }
                return true;
            }
        },

        /**
         * supports
         * 
         * @access  public
         * @var     Object
         */
        supports: {

            /**
             * downloadBlocking
             * 
             * @access  public
             * @return  Boolean
             */
            // downloadBlocking: function() {
            //     return true;
            // },

            /**
             * history
             * 
             * @access  public
             * @return  Boolean
             */
            history: function() {
                // return true;
                // if (FrameworkUtils.getPageView().usePushStateHistory() === false) {
                //     return false;
                // }
                if (window.history === null) {
                    return false;
                }
                if (window.history === undefined) {
                    return false;
                }
                if (window.history.pushState === null) {
                    return false;
                }
                if (window.history.pushState === undefined) {
                    return false;
                }
                return true;
            },

            /**
             * share
             * 
             * @see     https://developer.mozilla.org/en-US/docs/Web/API/Navigator/share
             * @access  public
             * @return  Boolean
             */
            share: function() {
                if (window.navigator.share === null) {
                    return false;
                }
                if (window.navigator.share === undefined) {
                    return false;
                }
                return true;
            },

            /**
             * touch
             * 
             * @access  public
             * @return  Boolean
             */
            touch: function() {
                if (window.matchMedia('(pointer: coarse)').matches === true) {
                    return true;
                }
                return false;
            }
        },

        /**
         * unfreeze
         * 
         * @access  public
         * @return  Boolean
         */
        // unfreeze: function() {
        //     if (__frozen === false) {
        //         return false;
        //     }
        //     __removeFreezeKeydownEvent();
        //     __frozen = false;
        //     var $body = document.body;
        //     $body.classList.remove('frozen');
        //     return true;
        // }
    };
})();

/**
 * WindowUtils
 * 
 * @access  public
 * @var     Object
 */
window.WindowUtils = (function() {

    /**
     * Properties (private)
     * 
     */

    /**
     * __redirectApproach
     * 
     * @access  private
     * @var     String (default: '_blank')
     */
    var __redirectApproach = '_blank';

    /**
     * __string
     * 
     * @access  private
     * @var     String (default: 'WindowUtils')
     */
    var __string = 'WindowUtils';

    /**
     * Methods (private)
     * 
     */

    /**
     * __openDestination
     * 
     * @access  private
     * @param   String destination
     * @param   undefined|String redirectApproach
     * @return  Boolean
     */
    var __openDestination = function(destination, redirectApproach) {
        redirectApproach = redirectApproach || __redirectApproach;
        if (redirectApproach === '_blank') {
            window.open(destination);
            return true;
        }
        window.location.href = destination;
        return true;
    };

    /**
     * Methods (public)
     * 
     */
    return {

        /**
         * download
         * 
         * @access  public
         * @param   String destination
         * @param   undefined|String redirectApproach
         * @return  void
         */
        download: function(destination, redirectApproach) {
            // AudioUtils.play('duck-quack-01.mp3');
            CookieUtils.increment('downloadCount');
            __openDestination(destination, redirectApproach);
            DataUtils.delay(1000).then(AuthUtils.syncUser);
        },

        /**
         * smartDownload
         * 
         * Determines which method to use for opening a link based on whether we
         * believe they've opened a link before (via cookies).
         * 
         * @note    The share-check is actually done to try and detect Safari.
         *          Safari doesn't close new-tabs that trigger a download. They
         *          also don't have download blocking, so it's actually ideal to
         *          prevent new tabs for it. Ideally, this should be named
         *          something like "likelySafari" to make it more semantically
         *          comprehensive.
         * @todo    Read the above note
         * @access  public
         * @param   String destination
         * @return  Boolean
         */
        smartDownload: function(destination) {
            if (UserAgentUtils.supports.touch() === true) {
                var redirectApproach = '_self';
                WindowUtils.download(destination, redirectApproach);
                return false;
            }
            if (UserAgentUtils.supports.share() === true) {
                var redirectApproach = '_self';
                WindowUtils.download(destination, redirectApproach);
                return false;
            }
            var smartOpenHasOccurred = CookieUtils.get('smartOpenHasOccurred'),
                redirectApproach = '_self';
            if (smartOpenHasOccurred === true) {
                redirectApproach = '_blank';
            }
            WindowUtils.download(destination, redirectApproach);
            CookieUtils.set('smartOpenHasOccurred', true);
            return true;
        }
    };
})();
window.DependencyLoader.push(['Base'], function() {

    /**
     * BaseView
     * 
     * @fires   elementHideStackUtils/run
     * @extends Base
     */
    window.BaseView = Base.extend({

        /**
         * Properties
         * 
         */

        /**
         * _$element
         * 
         * @access  protected
         * @var     null|HTMLElement (default: null)
         */
        _$element: null,

        /**
         * _$popover
         * 
         * @access  protected
         * @var     null|HTMLElement (default: null)
         */
        _$popover: null,

        /**
         * _autoFocusSelector
         * 
         * @access  protected
         * @var     null|String (default: null)
         */
        _autoFocusSelector: null,

        /**
         * _events
         * 
         * @access  protected
         * @var     Function
         */
        _events: function() {
            return {

                /**
                 * handleAnchorUpgradeFlow
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                // handleAnchorUpgradeFlow: function(event, $element) {
                //     var path = $element.getAttribute('href');
                //     if (AuthUtils.getUser() === null) {
                //         path = encodeURIComponent(path);
                //         window.location.href = '/signup?redirectPath=' + (path);
                //         __Iconduck.page.hideAccountPopover();
                //         return true;
                //     }
                //     window.location.href = path;
                //     return true;
                // },

                /**
                 * handleLoginFlow
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                handleLoginFlow: function(event, $element) {
                    var path = window.location.pathname,
                        path = encodeURIComponent(path);
                    window.location.href = '/login?redirectPath=' + (path);
                    __Iconduck.page.hideAccountPopover();
                },

                /**
                 * handleLogoutFlow
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                handleLogoutFlow: function(event, $element) {
                    ModalUtils.showBusy();
                    AuthUtils.getUser().logout().then(function() {
                        window.location.href = '/login';
                    });
                },

                /**
                 * handleSignUpFlow
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                handleSignUpFlow: function(event, $element) {
                    var path = window.location.pathname,
                        path = encodeURIComponent(path);
                    window.location.href = '/signup?redirectPath=' + (path);
                    __Iconduck.page.hideAccountPopover();
                },

                /**
                 * reloadPage
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                reloadPage: function(event, $element) {
                    window.location.reload();
                },

                /**
                 * showAPIModal
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                showAPIModal: function(event, $element) {
                    ModalUtils.showAPI();
                },

                /**
                 * showBlockUserModal
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                showBlockUserModal: function(event, $element) {
                    ModalUtils.showBlockUser();
                },

                /**
                 * showDownloadPopover
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                showDownloadPopover: function(event, $element) {
                    this._showDownloadPopover();
                },

                /**
                 * showImportVectorModal
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                showImportVectorModal: function(event, $element) {
                    var publicId = $element.getAttribute('data-vector-public-id'),
                        vector = FrameworkUtils.getActiveRecord(publicId);
                    ModalUtils.showImportVector(vector);
                },

                /**
                 * showMailingListModal
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                showMailingListModal: function(event, $element) {
                    ModalUtils.showMailingList();
                },

                /**
                 * showQueryVectorSetVectors
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                showQueryVectorSetVectors: function(event, $element) {
                    var vectorSet = this.getData().vectorSet;
                    ModalUtils.showQueryVectorSetVectors(vectorSet);
                },

                /**
                 * showSettingsModal
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                showSettingsModal: function(event, $element) {
                    ModalUtils.showSettings();
                    __Iconduck.page.hideAccountPopover();
                }
            };
        },

        /**
         * _killSwitchExemptClickHandlerKeys
         * 
         * @access  protected
         * @var     Array (default: [])
         */
        _killSwitchExemptClickHandlerKeys: [],

        /**
         * _popover
         * 
         * @access  protected
         * @var     null|BasePopoverComponentView (default: null)
         */
        _popover: null,

        /**
         * _properties
         * 
         * @access  protected
         * @var     Object (default: {})
         */
        _properties: {},

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'BaseView')
         */
        _string: 'BaseView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @note    this._events should not be set to the empty object. Normally
         *          I would to prevent cross-object instantiation issues, but I
         *          here because it would because this object is usually defined
         *          within the class (?).
         * @note    Ordered
         * @access  public
         * @param   HTMLElement $element
         * @return  void
         */
        init: function($element) {
            this._super();
            this._$element = $element;
            FrameworkUtils.setupComponents($element);
            // this._$element = $element;
            this._properties = {};
            this._addClickEventListeners();
            this._setupTooltips();
            this._setupDynamicElements();
            this._storeView();
            this._events = this._events();
        },

        /**
         * __action
         * 
         * @access  private
         * @param   String value
         * @param   undefined|Boolean all (default: false)
         * @return  null|HTMLElement|Array
         */
        __action: function(value, all) {
            all = all || false;
            var selector = '[data-action="' + (value) + '"]',
                found = this.__find(selector, all);
            return found;
        },

        /**
         * __all
         * 
         * @see     https://developer.mozilla.org/en-US/docs/Web/API/Element/querySelectorAll
         * @access  private
         * @param   String selector
         * @return  Array
         */
        __all: function(selector) {
            var $element = this._$element,
                $elements = $element.querySelectorAll(selector);
            $elements = Array.from($elements);
            return $elements;
        },

        /**
         * getComponent
         * 
         * @access  public
         * @param   String componentName
         * @return  null|BaseComponentView
         */
        getComponent: function(componentName) {
            componentName = DataUtils.ucfirst(componentName);
            var selector = '[data-component-name="' + (componentName) + '"]',
                $element = this.__find(selector);
            if ($element === null) {
                return null;
            }
            var view = $element.getView();
            return view;
        },

        /**
         * __components
         * 
         * @access  private
         * @param   String componentName
         * @return  null|Array
         */
        __components: function(componentName) {
            componentName = DataUtils.ucfirst(componentName);
            var selector = '[data-component-name="' + (componentName) + '"]',
                all = true,
                $element = this.__find(selector, all);
            return $element;
        },

        /**
         * __find
         * 
         * @see     https://developer.mozilla.org/en-US/docs/Web/API/Element/querySelectorAll
         * @access  private
         * @param   String selector
         * @param   undefined|Boolean all (default: false)
         * @return  null|HTMLElement|Array
         */
        __find: function(selector, all) {
            all = all || false;
            var $element = this._$element;
            if (all === false) {
                var $found = $element.querySelector(selector);
                return $found;
            }
            var $found = $element.querySelectorAll(selector),
                found = Array.from($found);
            return found;
        },

        /**
         * __getClickHandler
         * 
         * @access  private
         * @param   String clickHandlerEventKey
         * @param   HTMLElement $element
         * @return  Function
         */
        __getClickHandler: function(clickHandlerEventKey, $element) {
            var response = function(event) {
                event.preventDefault();
                var killSwitchExemptClickHandlerKeys = this._killSwitchExemptClickHandlerKeys;
                if (__Iconduck.page.dead() === true && killSwitchExemptClickHandlerKeys.includes('reload') === false) {
                    return false;
                }
                var args = [event, $element];
                if (clickHandlerEventKey !== 'null') {
                    if (this._events[clickHandlerEventKey] === undefined) {
                        var msg = 'Invalid clickHandlerEventKey: ' + (clickHandlerEventKey);
                        throw new Error(msg);
                    }
                    this._events[clickHandlerEventKey].apply(this, args);
                }
            };
            response = response.bind(this);
            return response;
        },

        /**
         * __id
         * 
         * @access  private
         * @param   String id
         * @return  null|HTMLElement
         */
        __id: function(id) {
            var $element = this._$element,
                selector = '[id="' + (id) + '"]',
                $found = $element.querySelector(selector);
            return $found;
        },

        /**
         * __data
         * 
         * @access  private
         * @param   String dataAttributeKey
         * @param   Boolean all
         * @return  null|mixed
         */
        __data: function(dataAttributeKey, all) {
            var selector = '[data-' + (dataAttributeKey) + ']',
                $elements = this.__find(selector, all);
            return $elements;
        },

        /**
         * __dataName
         * 
         * @access  private
         * @param   String dataName
         * @return  null|HTMLElement
         */
        __dataName: function(dataName) {
            var name = 'data[' + (dataName) + ']',
                response = this.__name(name);
            return response;
        },

        /**
         * __lookup
         * 
         * @access  private
         * @param   String value
         * @param   undefined|Boolean all (default: false)
         * @return  null|HTMLElement|Array
         */
        __lookup: function(value, all) {
            all = all || false;
            var selector = '[data-lookup="' + (value) + '"]',
                found = this.__find(selector, all);
            return found;
        },

        /**
         * __name
         * 
         * @access  private
         * @param   String name
         * @return  null|HTMLElement
         */
        __name: function(name) {
            var selector = '[name="' + (name) + '"]',
                $element = this.__find(selector);
            return $element;
        },

        /**
         * __view
         * 
         * @access  private
         * @param   HTMLElement $element,
         * @param   String viewName
         * @return  null|BaseView
         */
        // __view: function($element) {//, viewName) {
        //     var data = $element.data || {},
        //         view = data.view || null;
        //     return view;
        //     // var data = $element.data || {},
        //     //     view = data[viewName] || null;
        //     // return view;
        // },

        /**
         * _addClickEventListeners
         * 
         * @see     https://developer.mozilla.org/en-US/docs/Web/API/Element/querySelectorAll
         * @access  protected
         * @return  void
         */
        _addClickEventListeners: function() {
            var $element = this._$element,
                selector = '[data-click]',
                $elements = $element.querySelectorAll(selector),
                events = this._events,
                view = this;
            $elements = Array.from($elements);
            for ($element of $elements) {
                var data = $element.data || {},
                    considered = data.considered || false;
                if (considered === true) {
                    continue;
                }
                // var data = $element.closest('[data-component-name]').data;
                // if (data === undefined) {
                //     continue;
                // }
                $element.data = $element.data || {};
                // var view = data.view;
                $element.data.considered = true;
                var clickHandlerEventKey = $element.getAttribute('data-click'),
                    handler = this.__getClickHandler(clickHandlerEventKey, $element)
                    // handler = view.__getClickHandler(clickHandlerEventKey, $element);
                $element.addEventListener('click', handler);
            }
        },

        /**
         * _addHiddenClass
         * 
         * @access  protected
         * @return  void
         */
        _addHiddenClass: function() {
            this._$element.addClass('display-none');
        },

        /**
         * _drawPopover
         * 
         * @access  protected
         * @param   String templateName
         * @param   Object data
         * @return  Boolean
         */
        _drawPopover: function(templateName, data) {
            if (this._$popover !== null) {
                return false;
            }
            var $popover = ElementUtils.renderTemplate(templateName, data),
                selectors = [];
            selectors.push('[data-component-name="VectorGroupBlock"].loaded');
            selectors.push('div[data-component-name]:not([data-component-name="VectorGroupBlock"])');
            selectors.push('div.block');
            var selector = selectors.join(','),
                $parent = this._$element.closest(selector);
            $parent.append($popover);
            this._$popover = $popover;
            return true;
        },

        /**
         * _getAutoFocusTarget
         * 
         * @access  protected
         * @return  null|HTMLElement
         */
        _getAutoFocusTarget: function() {
            if (UserAgentUtils.supports.touch() === true) {
                return null;
            }
            var selectors = [];
            // selectors.push('input[type="email"]');
            selectors.push('input[type="email"][value=""]:not([readonly]):not(.not-focusable)');
            selectors.push('input[type="email"]:not([readonly]).always-focusable');
            selectors.push('input[type="password"]:not(.not-focusable)');
            selectors.push('input[type="search"]:not([readonly]):not(.not-focusable)');
            selectors.push('input[type="text"]:not([readonly]):not(.not-focusable)');
            selectors.push('input[type="url"]:not([readonly]):not(.not-focusable)');
            selectors.push('select:not(.not-focusable)');
            var modalButtonAutoFocus = ConfigUtils.getPublicValue('uiux', 'modalButtonAutoFocus');
            if (modalButtonAutoFocus === true || AuthUtils.admin() === true) {
                selectors.push('.button:not(.not-focusable)');
            }
            var selector = selectors.join(','),
                selector = this._autoFocusSelector || selectors,
                $element = this.__find(selector);
            return $element;
        },

        /**
         * _lowerCaseFirstLetter
         * 
         * @access  protected
         * @param   String str
         * @return  String
         */
        _lowerCaseFirstLetter: function(str) {
            str = str.charAt(0).toLowerCase() + str.slice(1);
            return str;
        },

        /**
         * _setupDynamicElements
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupDynamicElements: function() {
            DynamicElementUtils.setup(this)
            return true;
        },

        /**
         * _setupPopover
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupPopover: function() {
            if (this._popover !== null) {
                return false;
            }
            var $popover = this._$popover,
                popover = $popover.data.view,
                $reference = this._$element;
            popover.setupPopper($reference);
            this._popover = popover;
            return true;
        },

        /**
         * _setupTooltips
         * 
         * @see     https://atomiks.github.io/tippyjs/v5/creating-tooltips/
         * @access  protected
         * @return  Boolean
         */
        _setupTooltips: function() {
            if (UserAgentUtils.supports.touch() === true) {
                return false;
            }
            var selectors = [];
            selectors.push('[data-tooltip="1"]');
            var selector = selectors.join(','),
                hideOnClick = false,
                $elements = this.__find(selector, true) || [];
            for (var $element of $elements) {
                var placement = $element.getAttribute('data-tooltip-placement') || 'bottom',
                    interactive = $element.getAttribute('data-tooltip-interactive') === '1' || false;
                tippy($element, {
                    allowHTML: true,
                    hideOnClick: hideOnClick,
                    placement: placement,
                    interactive: interactive,
                    content: function($el) {
                        return $el.getAttribute('data-tooltip-content');
                    }
                });
                $element.setAttribute('data-tooltip', '0');
            }
            return true;
        },

        /**
         * _storeView
         * 
         * @access  protected
         * @return  void
         */
        _storeView: function() {
            this._$element.data = this._$element.data || {};
            // var key = this._string;
            // key = this._lowerCaseFirstLetter(key);
            // this._$element.data[key] = this._$element.data.view = this;
            this._$element.data.view = this;
        },

        /**
         * _removeHiddenClass
         * 
         * @access  protected
         * @return  void
         */
        _removeHiddenClass: function() {
            this._$element.removeClass('display-none');
        },

        /**
         * _toggleHiddenClass
         * 
         * @access  protected
         * @return  void
         */
        _toggleHiddenClass: function() {
            this._$element.classList.toggle('display-none');
        },

        /**
         * _updateTooltip
         * 
         * @see     https://stackoverflow.com/questions/71985677/change-tooltip-content-by-tippy-js-v6
         * @access  protected
         * @param   String content
         * @return  Boolean
         */
        _updateTooltip: function(content) {
            var tippy = this._$element._tippy;
            if (tippy === undefined) {
                this._$element.setAttribute('data-tooltip-content', content);
                return false;
            }
            tippy.setContent(content);
            return true;
        },

        /**
         * autoFocus
         * 
         * @access  public
         * @return  Boolean
         */
        autoFocus: function() {
            var $element = this._getAutoFocusTarget();
            if ($element === null) {
                return false;
            }
            $element.focus();
            var value = $element.value;
            $element.value = '';
            $element.value = value;
            return true;
        },

        /**
         * autoShowMailingListModal
         * 
         * @note    The delay is because sometimes it feels too fast that the
         *          mailing list modal shows up. This is especially the case on
         *          iOS whereby it takes a second for the browser to prompt you
         *          to download/view the file.
         * @access  public
         * @return  Boolean
         */
        autoShowMailingListModal: function() {

            // Visitor is logged in; bail
            var tokenPublicId = CookieUtils.get('token.publicId', 'server');
            if (tokenPublicId !== undefined) {
                return false;
            }

            // Visitor submitted their email address; bail
            var userPublicId = CookieUtils.get('userPublicId');
            if (userPublicId !== undefined) {
                return false;
            }

            // Mailing list modal never show; prompt
            var mailingListModalShown = CookieUtils.get('mailingListModalShown'),
                mailingListAutoShowDelay = ConfigUtils.getPublicValue('uiux', 'mailingListAutoShowDelay');
            if (mailingListModalShown === undefined) {
                var modal = ModalUtils.showMailingList();
                modal.hide();
                var fn = modal.show.bind(modal);
                DataUtils.delay(mailingListAutoShowDelay).then(fn);
                // _.delay(fn, mailingListAutoShowDelay);
                return true;
            }

            // Download count interval has been reached; prompt
            var downloadCount = CookieUtils.get('downloadCount'),
                mailingListDownloadCountIntervalPrompt = ConfigUtils.getPublicValue('uiux', 'mailingListDownloadCountIntervalPrompt');
            if ((downloadCount % mailingListDownloadCountIntervalPrompt) === 0) {
                var modal = ModalUtils.showMailingList();
                modal.hide();
                var fn = modal.show.bind(modal);
                DataUtils.delay(mailingListAutoShowDelay).then(fn);
                // _.delay(fn, mailingListAutoShowDelay);
                return true;
            }

            // Bail
            return false;
        },

        /**
         * autoShowPromotionModal
         * 
         * @note    The delay is because sometimes it feels too fast that the
         *          mailing list modal shows up. This is especially the case on
         *          iOS whereby it takes a second for the browser to prompt you
         *          to download/view the file.
         * @access  public
         * @return  Boolean
         */
        autoShowPromotionModal: function() {

            // Bail if not active
            if (ConfigUtils.getPublicValue('uiux', 'promotionModalActive') === false) {
                return false;
            }

            // Promotion modal never show; prompt
            var promotionModalShown = CookieUtils.get('promotionModalShown'),
                promotionModalAutoShowDelay = ConfigUtils.getPublicValue('uiux', 'promotionModalAutoShowDelay') || 1500;
            if (promotionModalShown === undefined) {
                var modal = ModalUtils.showPromotion();
                modal.hide();
                var fn = modal.show.bind(modal);
                DataUtils.delay(promotionModalAutoShowDelay).then(fn);
                return true;
            }

            // Download count interval has been reached; prompt
            var downloadCount = CookieUtils.get('downloadCount'),
                promotionModalDownloadCountIntervalPrompt = ConfigUtils.getPublicValue('uiux', 'promotionModalDownloadCountIntervalPrompt') || 4;
            if ((downloadCount % promotionModalDownloadCountIntervalPrompt) === 0) {
                var modal = ModalUtils.showPromotion();
                modal.hide();
                var fn = modal.show.bind(modal);
                DataUtils.delay(promotionModalAutoShowDelay).then(fn);
                return true;
            }

            // Bail
            return false;
        },

        /**
         * getElement
         * 
         * @access  public
         * @return  HTMLElement
         */
        getElement: function() {
            var $element = this._$element;
            return $element;
        },

        /**
         * getPopover
         * 
         * @access  public
         * @return  null|BasePopoverComponentView
         */
        getPopover: function() {
            var popover = this._popover;
            return popover;
        },

        /**
         * getProperties
         * 
         * @access  public
         * @return  Object
         */
        getProperties: function() {
            var properties = this._properties;
            return properties;
        },

        /**
         * getProperty
         * 
         * @access  public
         * @param   String key
         * @return  undefined|mixed
         */
        getProperty: function(key) {
            var value = this._properties[key];
            return value;
        },

        /**
         * setProperty
         * 
         * @access  public
         * @param   String key
         * @param   String value
         * @return  void
         */
        setProperty: function(key, value) {
            this._properties[key] = value;
        }
    });
});
window.DependencyLoader.push(['BaseView'], function() {

    /**
     * BaseComponentView
     * 
     * @fires   formState/change
     * @fires   formState/change/idle
     * @fires   formState/change/processing
     * @fires   formState/change/error
     * @fires   formState/change/success
     * @fires   state/change
     * @fires   state/change/$stateKey
     * @extends BaseView
     */
    window.BaseComponentView = BaseView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _formStateKey
         * 
         * @access  protected
         * @var     null|String (default: null)
         */
        _formStateKey: null,

        /**
         * _stateKey
         * 
         * @access  protected
         * @var     null|String (default: null)
         */
        _stateKey: null,

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'BaseComponentView')
         */
        _string: 'BaseComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element);
            this._data = data;
        },

        /**
         * _getState
         * 
         * @access  protected
         * @param   String stateKey
         * @return  BaseStateComponentView
         */
        _getState: function(stateKey) {
            var selector = '[data-state="' + (stateKey) + '"]',
                $state = this.__find(selector),
                state = $state.data.view;
            return state;
        },

        /**
         * _setFormState
         * 
         * @access  protected
         * @param   String formStateKey
         * @return  Boolean
         */
        _setFormState: function(formStateKey) {
            var $element = this._$element,
                currentFormStateKey = $element.getAttribute('data-form-state');
            if (currentFormStateKey === formStateKey) {
                return false;
            }
            this._formStateKey = formStateKey;
            $element.setAttribute('data-form-state', formStateKey);
            this.triggerCustomEvent('formState/change', [formStateKey]);
            var customEventName = 'formState/change/' + (formStateKey);
            this.triggerCustomEvent(customEventName);
            return true;
        },

        /**
         * _setState
         * 
         * @access  protected
         * @param   String stateKey
         * @return  Boolean
         */
        _setState: function(stateKey) {
            var $element = this._$element,
                currentStateKey = $element.getAttribute('data-state');
            if (currentStateKey === stateKey) {
                return false;
            }
            this._stateKey = stateKey;
            $element.setAttribute('data-state', stateKey);
            this.triggerCustomEvent('state/change', [stateKey]);
            var customEventName = 'state/change/' + (stateKey);
            this.triggerCustomEvent(customEventName);
            return true;
        },

        /**
         * _validElementHideKeyboardEvent
         * 
         * @see     https://sentry.io/organizations/iconduck/issues/3654248790
         * @see     https://stackoverflow.com/questions/19669786/check-if-element-is-visible-in-dom
         * @note    The offsetParent check is done because when Uppy is hidden,
         *          it's not actually removed from the DOM.
         * @access  protected
         * @param   Event event
         * @return  Boolean
         */
        _validElementHideKeyboardEvent: function(event) {
            var $uppy = __Iconduck.page.__find('.uppy-Root', true).last();
            if ($uppy !== null && $uppy.offsetParent !== null) {
                return false;
            }
            var code = event.code || '';
            code = code.toLowerCase();
            if (code !== 'escape') {
                return false;
            }
            var $target = event.target,
                tagName = $target.tagName || '',
                tagName = tagName.toLowerCase();
            if (tagName === 'textarea') {
                return false;
            }
            if (tagName === 'input') {
                if ($target.type === 'email') {
                    return false;
                }
                if ($target.type === 'password') {
                    return false;
                }
                if ($target.type === 'search') {
                    // return false;
                }
                if ($target.type === 'text') {
                    return false;
                }
                if ($target.type === 'url') {
                    return false;
                }
            }
            return true;
        },

        /**
         * _validElementHidePointerEvent
         * 
         * @access  protected
         * @param   Event event
         * @return  Boolean
         */
        _validElementHidePointerEvent: function(event) {
            var $element = this._$element,
                $triggerElement = event.target;
            if ($element === $triggerElement) {
                return false;
            }
            var contained = $element.contains($triggerElement);
            if (contained === true) {
                return false;
            }
            if (this._validHideTriggerElement($triggerElement) === false) {
                return false;
            }
            return true;
        },

        /**
         * _validHideTriggerElement
         * 
         * This method exists to allow for exceptions for what should cause a
         * hide action.
         * 
         * For example, when a modal's overlay is clicked on, it should trigger
         * a hide event for that modal. But that's an exception: most of the
         * time, the only thing that should trigger a hide event is clicking
         * _outside_ an element.
         * 
         * @access  protected
         * @param   HTMLElement $triggerElement
         * @return  Boolean
         */
        _validHideTriggerElement: function($triggerElement) {
            var $growl = $triggerElement.closest('[data-component-name="GrowlNotification"]'),
                $uppy = $triggerElement.closest('.uppy-Root');
            if ($growl === null && $uppy === null) {
                return true;
            }
            return false;
        },

        /**
         * destroy
         * 
         * @access  public
         * @return  Boolean
         */
        destroy: function() {
            this._$element.remove();
            this.clearCustomEventListeners();
            FrameworkUtils.destroyComponent(this);
            return true;
        },

        /**
         * getAttribute
         * 
         * @access  public
         * @param   String attributeKey
         * @return  mixed
         */
        getAttribute: function(attributeKey) {
            var $element = this._$element,
                attributeName = 'data-component-' + (attributeKey),
                value = $element.getAttribute(attributeName);
            return value;
        },

        /**
         * removeAttribute
         * 
         * @access  public
         * @param   String attributeKey
         * @return  Boolean
         */
        removeAttribute: function(attributeKey) {
            var $element = this._$element,
                attributeName = 'data-component-' + (attributeKey);
            $element.removeAttribute(attributeName);
            return true;
        },

        /**
         * setAttribute
         * 
         * @access  public
         * @param   String attributeKey
         * @param   String attributeValue
         * @return  Boolean
         */
        setAttribute: function(attributeKey, attributeValue) {
            var $element = this._$element,
                attributeName = 'data-component-' + (attributeKey);
            $element.setAttribute(attributeName, attributeValue);
            return true;
        },

        /**
         * validElementHideEvent
         * 
         * @access  public
         * @param   Event event
         * @return  Boolean
         */
        validElementHideEvent: function(event) {
            if (event instanceof KeyboardEvent) {
                var response = this._validElementHideKeyboardEvent(event);
                return response;
            }
            if (event instanceof MouseEvent) {
                var response = this._validElementHidePointerEvent(event);
                return response;
            }
            if (event instanceof PointerEvent) {
                var response = this._validElementHidePointerEvent(event);
                return response;
            }
            return false;
        }
    });
});
window.DependencyLoader.push(['BaseBlockComponentView'], function() {

    /**
     * VectorSetDesignerRowBlockComponentView
     * 
     * @extends BaseBlockComponentView
     */
    window.VectorSetDesignerRowBlockComponentView = BaseBlockComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _events
         * 
         * @access  protected
         * @var     Function
         */
        _events: function() {
            return Object.assign(this._super(), {

                /**
                 * deleteVectorSetDesigner
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                deleteVectorSetDesigner: function(event, $element) {
                    this._deleteVectorSetDesigner();
                }
            });
        },

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'VectorSetDesignerRowBlockComponentView')
         */
        _string: 'VectorSetDesignerRowBlockComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * _deleteVectorSetDesigner
         * 
         * @access  protected
         * @return  Boolean
         */
        _deleteVectorSetDesigner: function() {
            var primary = 'Are you sure?',
                secondary = 'This cannot be undone.',
                handler = this._handleDeleteEvent.bind(this);
            UserAgentUtils.confirm(primary, secondary).then(handler);
            return true;
        },

        /**
         * _destroyManageVectorSetDesignersModal
         * 
         * @access  protected
         * @return  Boolean
         */
        _destroyManageVectorSetDesignersModal: function() {
            var modalKey = 'ManageVectorSetDesigners',
                modal = ModalUtils.getModal(modalKey);
            modal.destroy();
            return true;
        },

        /**
         * _getVectorSetDesigner
         * 
         * @access  protected
         * @return  VectorSetDesignerActiveRecord
         */
        _getVectorSetDesigner: function() {
            var publicId = this.getAttribute('vector-set-designer-public-id'),
                activeRecord = FrameworkUtils.getActiveRecord(publicId);
            return activeRecord;
        },

        /**
         * _handleDeleteEvent
         * 
         * @access  protected
         * @return  Boolean
         */
        _handleDeleteEvent: function() {
            var vectorSetDesigner = this._getVectorSetDesigner(),
                handler = this._handleSuccessFlow.bind(this);
            vectorSetDesigner.delete().then(handler);
            return true;
        },

        /**
         * _handleSuccessFlow
         * 
         * @access  protected
         * @return  Boolean
         */
        _handleSuccessFlow: function() {
            this._destroyManageVectorSetDesignersModal();
            this._showManageVectorSetDesignersModal();
            return true;
        },

        /**
         * _showManageVectorSetDesignersModal
         * 
         * @access  protected
         * @return  Boolean
         */
        _showManageVectorSetDesignersModal: function() {
            var vectorSet = this._getVectorSetDesigner().getVectorSet();
            ModalUtils.showManageVectorSetDesigners(vectorSet);
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseBlockComponentView'], function() {

    /**
     * VectorSetSubsetRowBlockComponentView
     * 
     * @extends BaseBlockComponentView
     */
    window.VectorSetSubsetRowBlockComponentView = BaseBlockComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _events
         * 
         * @access  protected
         * @var     Function
         */
        _events: function() {
            return Object.assign(this._super(), {

                /**
                 * applyAll
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                applyAll: function(event, $element) {
                    this._applyAll();
                },

                /**
                 * deleteVectorSetSubset
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                deleteVectorSetSubset: function(event, $element) {
                    this._deleteVectorSetSubset();
                }
            });
        },

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'VectorSetSubsetRowBlockComponentView')
         */
        _string: 'VectorSetSubsetRowBlockComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this._addListChangeEventListener();
        },

        /**
         * _addListChangeEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addListChangeEventListener: function() {
            var $input = this.__dataName('list'),
                handler = this._handleListChangeEvent.bind(this);
            $input.addEventListener('change', function(event) {
                handler(event);
            });
            return true;
        },

        /**
         * _applyAll
         * 
         * @access  protected
         * @return  Boolean
         */
        _applyAll: function() {
            var primary = 'Are you sure?',
                secondary = 'This cannot be undone.',
                handler = this._handleApplyAllEvent.bind(this);
            UserAgentUtils.confirm(primary, secondary).then(handler);
            return true;
        },

        /**
         * _deleteVectorSetSubset
         * 
         * @access  protected
         * @return  Boolean
         */
        _deleteVectorSetSubset: function() {
            var primary = 'Are you sure?',
                secondary = 'This cannot be undone.',
                handler = this._handleDeleteEvent.bind(this);
            UserAgentUtils.confirm(primary, secondary).then(handler);
            return true;
        },

        /**
         * _destroyManageVectorSetSubsetsModal
         * 
         * @access  protected
         * @return  Boolean
         */
        _destroyManageVectorSetSubsetsModal: function() {
            var modalKey = 'ManageVectorSetSubsets',
                modal = ModalUtils.getModal(modalKey);
            modal.destroy();
            return true;
        },

        /**
         * _getVectorSetSubset
         * 
         * @access  protected
         * @return  VectorSetSubsetActiveRecord
         */
        _getVectorSetSubset: function() {
            var publicId = this.getAttribute('vector-set-subset-public-id'),
                activeRecord = FrameworkUtils.getActiveRecord(publicId);
            return activeRecord;
        },

        /**
         * _handleApplyAllEvent
         * 
         * @access  protected
         * @return  Boolean
         */
        _handleApplyAllEvent: function() {
            var vectorSetSubset = this._getVectorSetSubset(),
                handler = this._handleSuccessFlow.bind(this);
            ModalUtils.showBusy('Applying vector set subset to all vectors...');
            var publicId = this._getVectorSetSubset().get('vectorSet').publicId,
                path = '/vectorSets/' + (publicId) + '/queries/run',
                data = {};
            data.property = 'filepath';
            data.operator = 'LIKE';
            data.queries = '%%';
            data.conditionalOperator = 'OR';
            data.behavior = 'add';
            data.vectorSetSubsetId = vectorSetSubset.get('id');
            RequestUtils.post(path, data).then(handler);
            return true;
        },

        /**
         * _handleDeleteEvent
         * 
         * @access  protected
         * @return  Boolean
         */
        _handleDeleteEvent: function() {
            var vectorSetSubset = this._getVectorSetSubset(),
                handler = this._handleSuccessFlow.bind(this);
            ModalUtils.showBusy('Deleting vector set subset...');
            vectorSetSubset.delete().then(handler);
            return true;
        },

        /**
         * _handleListChangeEvent
         * 
         * @access  protected
         * @param   Object event
         * @return  Boolean
         */
        _handleListChangeEvent: function(event) {
            var vectorSetSubset = this._getVectorSetSubset(),
                checked = event.target.checked ? 1 : 0;
            vectorSetSubset.setColumn('list', checked);
            return true;
        },

        /**
         * _handleSuccessFlow
         * 
         * @access  protected
         * @return  Boolean
         */
        _handleSuccessFlow: function() {
            ModalUtils.hideBusy();
            this._destroyManageVectorSetSubsetsModal();
            this._showManageVectorSetSubsetsModal();
            return true;
        },

        /**
         * _showManageVectorSetSubsetsModal
         * 
         * @access  protected
         * @return  Boolean
         */
        _showManageVectorSetSubsetsModal: function() {
            var vectorSet = this._getVectorSetSubset().getVectorSet();
            ModalUtils.showManageVectorSetSubsets(vectorSet);
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseBlockComponentView'], function() {

    /**
     * AdminRecordRowBlockComponentView
     * 
     * @extends BaseBlockComponentView
     */
    window.AdminRecordRowBlockComponentView = BaseBlockComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'AdminRecordRowBlockComponentView')
         */
        _string: 'AdminRecordRowBlockComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        }
    });
});
window.DependencyLoader.push(['BaseComponentView'], function() {

    /**
     * BaseBlockComponentView
     * 
     * @extends BaseComponentView
     */
    window.BaseBlockComponentView = BaseComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'BaseBlockComponentView')
         */
        _string: 'BaseBlockComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        }
    });
});
window.DependencyLoader.push(['BaseBlockComponentView'], function() {

    /**
     * CollectionBlockComponentView
     * 
     * @extends BaseBlockComponentView
     */
    window.CollectionBlockComponentView = BaseBlockComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'CollectionBlockComponentView')
         */
        _string: 'CollectionBlockComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this._addDeleteEventListener();
        },

        /**
         * _addDeleteEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addDeleteEventListener: function(event) {
            var collection = this._getCollection(),
                handler = this._handleDeleteEvent.bind(this);
            collection.addCustomEventListenerOnce('delete/start', handler);
            return true;
        },

        /**
         * _handleDeleteEvent
         * 
         * @access  protected
         * @return  Boolean
         */
        _handleDeleteEvent: function() {
            this.destroy();
            return true;
        },

        /**
         * _getCollection
         * 
         * @access  protected
         * @return  CollectionActiveRecord
         */
        _getCollection: function(event) {
            var publicId = this.getAttribute('collection-public-id'),
                collection = FrameworkUtils.setActiveRecord(publicId, 'Collection');
            return collection;
        }
    });
});
window.DependencyLoader.push(['BaseBlockComponentView'], function() {

    /**
     * CollectionRowBlockComponentView
     * 
     * @extends BaseBlockComponentView
     */
    window.CollectionRowBlockComponentView = BaseBlockComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'CollectionRowBlockComponentView')
         */
        _string: 'CollectionRowBlockComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this._addClickEventListener();
            this._addContextMenuEventListener();
            this._addCollectionChangeEventListener();
            this._addCollectionItemsAddEventListener();
            this._addCollectionItemsRemoveEventListener();
            this.refresh();
        },

        /**
         * _addCollectionChangeEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addCollectionChangeEventListener: function() {
            var collection = this._data.collection,
                handler = this.refresh.bind(this);
            collection.addCustomEventListener('change', function(columnKey, columnValue) {
                handler();
            });
            return true;
        },

        /**
         * _addClickEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addClickEventListener: function() {
            var handler = this._handleClickEvent.bind(this);
            this._$element.addEventListener('click', function(event) {
                event.preventDefault();
                handler(event);
            });
            return true;
        },

        /**
         * _addContextMenuEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addContextMenuEventListener: function() {
            var handler = this._handleContextMenuEvent.bind(this);
            this._$element.addEventListener('contextmenu', function(event) {
                event.preventDefault();
                handler(event);
            });
            return true;
        },

        /**
         * _drawPopover
         * 
         * @access  protected
         * @return  Boolean
         */
        _drawPopover: function() {
            var templateName = 'CollectionContextMenuPopoverComponent',
                data = {};
            data.collection = this._data.collection;
            var response = this._super(templateName, data);
            return response;
        },

        /**
         * _addCollectionItemsAddEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addCollectionItemsAddEventListener: function() {
            var collectionItems = this._data.collection.getCollectionItems(),
                handler = this._handleVectorsAddEvent.bind(this);
            collectionItems.addCustomEventListener('add', handler);
            return true;
        },

        /**
         * _addCollectionItemsRemoveEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addCollectionItemsRemoveEventListener: function() {
            var collectionItems = this._data.collection.getCollectionItems(),
                handler = this._handleVectorsRemoveEvent.bind(this);
            collectionItems.addCustomEventListener('remove', handler);
            return true;
        },

        /**
         * _handleClickEvent
         * 
         * @access  protected
         * @param   Object event
         * @return  Boolean
         */
        _handleClickEvent: function(event) {
            var vector = this._data.vector,
                collection = this._data.collection,
                collectionItems = collection.getCollectionItems(),
                contains = collectionItems.contains(vector);
            if (contains === true) {
                collection.remove(vector);
                return true;
            }
            collection.add(vector);
            return true;
        },

        /**
         * _handleContextMenuEvent
         * 
         * @access  protected
         * @param   Object event
         * @return  Boolean
         */
        _handleContextMenuEvent: function(event) {
            this._drawPopover();
            this._setupPopover();
            this._popover.show();
            return true;
        },

        /**
         * _handleVectorsAddEvent
         * 
         * @access  protected
         * @return  Boolean
         */
        _handleVectorsAddEvent: function() {
            NotificationUtils.showSimpleGrowl('Icon added to collection')
            this.refresh();
            return true;
        },

        /**
         * _handleVectorsRemoveEvent
         * 
         * @access  protected
         * @return  Boolean
         */
        _handleVectorsRemoveEvent: function() {
            NotificationUtils.showSimpleGrowl('Icon removed from collection')
            this.refresh();
            return true;
        },

        /**
         * _updateCount
         * 
         * @access  protected
         * @return  Boolean
         */
        _updateCount: function() {
            var $count = this.__lookup('count'),
                collection = this._data.collection;
                count = collection.getCollectionItems().count();
            $count.innerText = count;
            return true;
        },

        /**
         * destroy
         * 
         * @access  public
         * @return  Boolean
         */
        destroy: function() {
            if (this._popover !== null) {
                this._popover.destroy();
            }
            this._super();
            return true;
        },

        /**
         * refresh
         * 
         * @access  public
         * @return  Boolean
         */
        refresh: function() {
            this._updateCount();
            var vector = this._data.vector;
            this._$element.removeClass('collection_row_block-pulse');
            if (this._data.collection.contains(vector) === true) {
                this._setState('selected');
                return true;
            }
            this._setState('idle');
            return true;
        },

        /**
         * scrollIntoView
         * 
         * @access  public
         * @return  Boolean
         */
        scrollIntoView: function() {
            var $element = this._$element;
            $element.scrollIntoView({
                behaviour: 'smooth',
                block: 'center',
                inline: 'nearest'
            });
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseBlockComponentView'], function() {

    /**
     * ColorPickerBlockComponentView
     * 
     * @see     https://github.com/Simonwep/pickr
     * @extends BaseBlockComponentView
     */
    window.ColorPickerBlockComponentView = BaseBlockComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _pickr
         * 
         * @access  protected
         * @var     null|Pickr (default: null)
         */
        _pickr: null,

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'ColorPickerBlockComponentView')
         */
        _string: 'ColorPickerBlockComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this._setupColorPicker();
        },

        /**
         * _getColorPickerDefaultProperties
         * 
         * @access  protected
         * @return  Object
         */
        _getColorPickerDefaultProperties: function() {
            var $element = this._$element,
                color = 'blue',
                defaultProperties = {
                    el: $element,
                    theme: 'nano',
                    default: color,
                    swatches: this._getColorPickerSwatches(),
                    container: '.im-app',
                    components: {
                        preview: true,
                        opacity: true,
                        hue: true,
                        interaction: {
                            input: true
                        }
                    }
                };
            return defaultProperties;
        },

        /**
         * _getColorPickerSwatches
         * 
         * @access  protected
         * @return  Array
         */
        _getColorPickerSwatches: function() {
            var swatches = [
                'rgba(244,  67,     54,     1.00)',
                'rgba(233,  30,     99,     0.95)',
                'rgba(156,  39,     176,    0.90)',
                'rgba(103,  58,     183,    0.85)',
                'rgba(63,   81,     181,    0.80)',
                'rgba(33,   150,    243,    0.75)',
                'rgba(3,    169,    244,    0.70)',
                'rgba(0,    188,    212,    0.70)',
                'rgba(0,    150,    136,    0.75)',
                'rgba(76,   175,    80,     0.80)',
                'rgba(139,  195,    74,     0.85)',
                'rgba(205,  220,    57,     0.90)',
                'rgba(255,  235,    59,     0.95)',
                'rgba(255,  193,    7,      1.00)'
            ];
            return swatches;
        },

        /**
         * _getDrawer
         * 
         * @access  proteted
         * @return  BaseDrawerComponentView
         */
        _getDrawer: function() {
            var $element = this._$element,
                $drawer = $element.closest('.im-drawer'),
                view = $drawer.getView();
            return view;
        },

        /**
         * _handleColorPickerChangeEvent
         * 
         * @access  protected
         * @param   Object color;
         * @return  Boolean
         */
        _handleColorPickerChangeEvent: function(color) {
            var pickr = this._pickr,
                $root = pickr.getRoot().root,
                $button = $root.querySelector('button'),
                rgba = color.toRGBA().toString();
            $button.setAttribute('style', '--pcr-color: ' + (rgba));
            return true;
        },

        /**
         * _setupColorPicker
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupColorPicker: function() {
            var drawer = this._getDrawer(),
                $element = this._$element,
                properties = this._getColorPickerDefaultProperties(),
                pickr = Pickr.create(properties),
                scope = this._$element.getAttribute('data-scope');
            this._pickr = pickr;
            drawer.setColorPicker(scope, this);
            var handler = this._handleColorPickerChangeEvent.bind(this);
            pickr.on('change', handler);
        },

        /**
         * setColorPickerColor
         * 
         * @access  public
         * @param   String color
         * @return  Boolean
         */
        setColorPickerColor: function(color) {
            this._pickr.setColor(color);
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseComponentView'], function() {

    /**
     * HeaderBlockComponentView
     * 
     * @extends BaseComponentView
     */
    window.HeaderBlockComponentView = BaseComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _$accountPopover
         * 
         * @access  protected
         * @var     null|HTMLElement (default: null)
         */
        _$accountPopover: null,

        /**
         * _accountPopover
         * 
         * @access  protected
         * @var     null|AccountPopoverComponentView (default: null)
         */
        _accountPopover: null,

        /**
         * _events
         * 
         * @access  protected
         * @var     Function
         */
        _events: function() {
            return Object.assign(this._super(), {

                /**
                 * showAccountPopover
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                showAccountPopover: function(event, $element) {
                    this._showAccountPopover();
                }
            });
        },

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'HeaderBlockComponentView')
         */
        _string: 'HeaderBlockComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this.autoFocus();
            this._resetInputValue();
            this._setupForm();
            this._drawAccountPopover();
            this._setupAccountPopover();
        },

        /**
         * _drawAccountPopover
         * 
         * @access  protected
         * @return  Boolean
         */
        _drawAccountPopover: function() {
            var templateName = 'AccountPopoverComponent',
                $accountPopover = ElementUtils.renderTemplate(templateName),
                $parent = this._$element;
            $parent.append($accountPopover);
            this._$accountPopover = $accountPopover;
            return true;
        },

        /**
         * _formSubmitEvaluator
         * 
         * @access  protected
         * @return  Boolean
         */
        _formSubmitEvaluator: function() {
            var searchInputVaue = this._getSearchInputValue();
            if (searchInputVaue === '') {
                var $input = this._getSearchInput();
                $input.value = '';
                $input.focus();
                return false;
            }
            return true;
        },

        /**
         * _getFormElement
         * 
         * @access  protected
         * @return  String
         */
        _getFormElement: function() {
            var $element = this._$element,
                $form = $element.querySelector('form');
            return $form;
        },

        /**
         * _getSearchInput
         * 
         * @access  protected
         * @return  HTMLInputElement
         */
        _getSearchInput: function() {
            var $element = this._$element,
                $input = $element.querySelector('input');
            return $input;
        },

        /**
         * _getSearchInputValue
         * 
         * @access  protected
         * @return  String
         */
        _getSearchInputValue: function() {
            var $input = this._getSearchInput(),
                value = $input.value,
                value = value.trim();
            return value;
        },

        /**
         * _resetInputValue
         * 
         * @access  protected
         * @return  Boolean
         */
        _resetInputValue: function() {
            var href = location.href;
            if (href.includes('query=') === true) {
                return false;
            }
            var $input = this._getSearchInput();
            $input.value = '';
            return true;
        },

        /**
         * _setupAccountPopover
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupAccountPopover: function() {
            var $accountPopover = this._$accountPopover,
                accountPopover = $accountPopover.data.view,
                $reference = this.__find('.profile');
            accountPopover.setupPopper($reference);
            this._accountPopover = accountPopover;
            return true;
        },

        /**
         * _setupForm
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupForm: function() {
            var $form = this.__find('form'),
                form = $form.getView(),//this.__view($form),//, 'baseFormComponentView'),
                handler = this._formSubmitEvaluator.bind(this);
            this._form = form;
            this._form.setProcessingDelay(null);
            this._form.setSubmitEvaluator(handler);
            return true;
        },

        /**
         * _showAccountPopover
         * 
         * @access  protected
         * @return  Boolean
         */
        _showAccountPopover: function() {
            this._accountPopover.show();
            return true;
        },

        /**
         * autoFocus
         * 
         * @see     https://stackoverflow.com/a/2345915
         * @access  public
         * @return  Boolean
         */
        autoFocus: function() {
            var pathname = location.pathname;
            if (pathname === '/') {
                var response = this._super(),
                    $element = this._getAutoFocusTarget(),
                    value = this._getSearchInputValue();
                // $element.value = '';
                // $element.value = value;
                return response;
            }
            if (pathname === '/search') {
                var response = this._super(),
                    $element = this._getAutoFocusTarget(),
                    value = this._getSearchInputValue();
                // $element.value = '';
                // $element.value = value;
                return response;
            }
            return false;
        },

        /**
         * getAccountPopover
         * 
         * @access  public
         * @return  AccountPopoverComponentView
         */
        getAccountPopover: function() {
            var accountPopover = this._accountPopover;
            return accountPopover;
        },

        /**
         * pulseForm
         * 
         * @access  public
         * @return  void
         */
        pulseForm: function() {
            var selector = 'form',
                $element = this.__find(selector);
            $element.addClass('pulse');
            $element.addClass('short');
            $element.addClass('small');
            setTimeout(function() {
                $element.removeClass('pulse');
                $element.removeClass('short');
                $element.removeClass('small');
            }, 800);
        },

        /**
         * pulseLikeIcon
         * 
         * @access  public
         * @return  void
         */
        pulseLikeIcon: function() {
            var selector = 'div.option.like a .icon',
                $element = this.__find(selector);
            $element.addClass('icon-red');
            $element.addClass('opacity-100');
            $element.addClass('pulse');
            setTimeout(function() {
                $element.removeClass('icon-red');
                $element.removeClass('opacity-100');
                $element.removeClass('pulse');
            }, 2000);
        }
    });
});
window.DependencyLoader.push(['BaseBlockComponentView'], function() {

    /**
     * VectorBlockComponentView
     * 
     * @extends BaseBlockComponentView
     */
    window.VectorBlockComponentView = BaseBlockComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'VectorBlockComponentView')
         */
        _string: 'VectorBlockComponentView',

        /**
         * _vector
         * 
         * @access  protected
         * @var     null|VectorActiveRecord
         */
        _vector: null,

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this._setupVector();
            this._addClickEventListener();
            this._addContextMenuEventListener();
            this._addPreviewCustomEventListener();
            this._addMouseenterEventListener();
            this._addMouseleaveEventListener();
            this._addToggleEventListener();
        },

        /**
         * _addClickEventListener
         * 
         * @access  protected
         * @return  void
         */
        _addClickEventListener: function() {
            var handler = this._handleClickEvent.bind(this);
            this._$element.addEventListener('click', function(event) {
                if (event.metaKey !== true) {
                    event.preventDefault();
                    handler();
                }
            });
        },

        /**
         * _addContextMenuEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addContextMenuEventListener: function() {
            var handler = this._handleContextMenuEvent.bind(this);
            this._$element.addEventListener('contextmenu', function(event) {
                event.preventDefault();
                handler(event);
            });
            return true;
        },

        /**
         * _addPreviewCustomEventListener
         * 
         * @access  protected
         * @return  void
         */
        _addPreviewCustomEventListener: function() {
            var vector = this._getVector(),
                $element = this._$element;
            vector.addCustomEventListener('preview', function(event) {
                var $elements = __Iconduck.page.__find('.vector.preview') || [];
                $elements.removeClass('preview');
                $element.addClass('preview');
            });
        },

        /**
         * _addMouseenterEventListener
         * 
         * @access  protected
         * @return  void
         */
        _addMouseenterEventListener: function() {
            var vector = this._vector;
            this._$element.addEventListener('mouseenter', function(event) {
                var pageView = __Iconduck.page;
                pageView.setProperty('activeVector', vector);
                // vector.preload();
            });
        },

        /**
         * _addMouseleaveEventListener
         * 
         * @access  protected
         * @return  void
         */
        _addMouseleaveEventListener: function() {
            this._$element.addEventListener('mouseleave', function(event) {
                var pageView = __Iconduck.page;
                pageView.setProperty('activeVector', null);
            });
        },

        /**
         * _addToggleEventListener
         * 
         * @access  protected
         * @return  void
         */
        _addToggleEventListener: function() {
            var vector = this._vector,
                handler = this._handleToggleEvent.bind(this);
            vector.addCustomEventListener('change/broken', handler);
            vector.addCustomEventListener('change/color', handler);
            vector.addCustomEventListener('change/displayShowContrast', handler);
            vector.addCustomEventListener('change/flagged', handler);
            vector.addCustomEventListener('change/solid', handler);
        },

        /**
         * _getImageElement
         * 
         * @access  protected
         * @return  HTMLImageElement
         */
        _getImageElement: function() {
            var $element = this._$element,
                $img = $element.querySelector('img');
            return $img;
        },

        /**
         * _getLoader
         * 
         * @access  protected
         * @return  null|LoaderView
         */
        _getLoader: function() {
            var $loader = document.querySelector('[data-component-name="LoaderTrigger"]');
            if ($loader === null) {
                return null;
            }
            var loaderView = $loader.data.loaderView;
            return loaderView;
        },

        /**
         * _getPreview
         * 
         * @access  protected
         * @return  PreviewModalView
         */
        _getPreview: function() {
            var previewModal = ModalUtils.getPreview();
            return previewModal;
        },

        /**
         * _getVector
         * 
         * @access  protected
         * @return  VectorActiveRecord
         */
        _getVector: function() {
            var publicId = this.getAttribute('public-id'),
                name = 'Vector',
                vector = FrameworkUtils.setActiveRecord(publicId, name);
            return vector;
        },

        /**
         * _getVectorGroup
         * 
         * @access  protected
         * @return  VectorGroupBlockView
         */
        _getVectorGroup: function() {
            var $element = this._$element,
                $vectorGroup = $element.closest('[data-component-name="VectorGroupBlock"]'),
                view = $vectorGroup.getView();// this.__view($vectorsGroup);//, 'vectorGroupBlockComponentView');
            return view;
        },

        /**
         * _getVectorGroupVectorsCollection
         * 
         * @access  protected
         * @return  VectorsCollection
         */
        _getVectorGroupVectorsCollection: function() {
            var vectorGroup = this._getVectorGroup(),
                vectors = vectorGroup.getVectors();
            return vectors;
        },

        /**
         * _handleClickEvent
         * 
         * @access  protected
         * @return  void
         */
        _handleClickEvent: function() {
            this.showPreviewModal();
            var path = this._getPath()
            this._vector.trackPushState(path);
        },

        /**
         * _drawPopover
         * 
         * @access  protected
         * @return  Boolean
         */
        _drawPopover: function() {
            var templateName = 'VectorContextMenuPopoverComponent',
                data = {};
            data.vector = this._getVector();
            var response = this._super(templateName, data);
            return response;
        },

        /**
         * _handleContextMenuEvent
         * 
         * @access  protected
         * @param   Object event
         * @return  Boolean
         */
        _handleContextMenuEvent: function(event) {
            var vector = this._getVector();
            vector.triggerCustomEvent('preview');
            this._drawPopover();
            this._setupPopover();
            this._popover.show();
            return true;
        },

        /**
         * _handleToggleEvent
         * 
         * @access  protected
         * @param   mixed value
         * @return  void
         */
        _handleToggleEvent: function(value) {
            this.refreshClasses();
        },

        /**
         * _setupVector
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupVector: function() {
            var $element = this._$element,
                publicId = $element.getAttribute('data-component-public-id'),
                publicData = {};
            publicData.publicId = publicId;
            var model = FrameworkUtils.getModel('Vector');
            this._vector = model.setActiveRecord(publicData);
            return true;
        },

        /**
         * refreshClasses
         * 
         * @access  public
         * @return  Boolean
         */
        refreshClasses: function() {
            var classes = this._vector.getStylePropertyClasses();
            classes.push('vector');
            this._$element.className = classes.join(' ');
            return true;
        },

        /**
         * _getPath
         * 
         * @access  protected
         * @return  String
         */
        _getPath: function() {
            var path = this._$element.getAttribute('href');
            return path;
        },

        /**
         * showPreviewModal
         * 
         * @access  public
         * @return  void
         */
        showPreviewModal: function() {
            var vector = this._vector,
                vectorsCollection = this._getVectorGroupVectorsCollection(),
                handler = ModalUtils.showPreview.bind(ModalUtils, vector, vectorsCollection);
            ModalUtils.showBusy();
            vector.preload().then(function() {
                ModalUtils.closeVisible();
            }).then(handler);
        }
    });
});
window.DependencyLoader.push(['BaseBlockComponentView'], function() {

    /**
     * VectorGroupBlockComponentView
     * 
     * @extends BaseBlockComponentView
     */
    window.VectorGroupBlockComponentView = BaseBlockComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _loader
         * 
         * @access  protected
         * @var     null|LoaderTriggerComponentView (default: null)
         */
        _loader: null,

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'VectorGroupBlockComponentView')
         */
        _string: 'VectorGroupBlockComponentView',

        /**
         * _vectors
         * 
         * @access  protected
         * @var     null|VectorsCollection (default: null)
         */
        _vectors: null,

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this._setupCollection();
            this._addCollectionAddEventListener();
        },

        /**
         * _addCollectionAddEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addCollectionAddEventListener: function() {
            var handler = this._handleCollectionAddEvent.bind(this);
            this._vectors.addCustomEventListener('add', handler);
            return true;
        },

        /**
         * _drawVectorBlock
         * 
         * @access  protected
         * @param   VectorActiveRecord vector
         * @return  void
         */
        _drawVectorBlock: function(vector) {
            var templateName = 'VectorBlockComponent',
                data = {};
            data.vector = vector;
            data.vectorGroupBlock = this;
            var $element = ElementUtils.renderTemplate(templateName, data),
                $parent = this._$element;
            $parent.appendChild($element);
        },

        /**
         * _getLoader
         * 
         * @access  protected
         * @return  null|LoaderTriggerComponentView
         */
        _getLoader: function() {
            var loader = this.getAttribute('loader').toInt();
            if (loader === 1) {
                var loader = FrameworkUtils.getComponentView('LoaderTrigger');
                return loader;
            }
            return null;
        },

        /**
         * _handleCollectionAddEvent
         * 
         * @access  protected
         * @param   VectorActiveRecord vector
         * @return  Boolean
         */
        _handleCollectionAddEvent: function(vector) {
            this._drawVectorBlock(vector);
            return true;
        },

        /**
         * _setupCollection
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupCollection: function() {
            var dataSet = [],
                $components = this.__components('vectorBlock');
            for (var $component of $components) {
                var publicData = {};
                publicData.publicId = $component.getAttribute('data-component-public-id');
                dataSet.push(publicData);
            }
            this._vectors = new VectorsCollection(dataSet);
            return true;
        },

        /**
         * getLoader
         * 
         * @access  public
         * @return  null|LoaderTriggerComponentView
         */
        getLoader: function() {
            var loader = this._loader;
            return loader;
        },

        /**
         * getVectors
         * 
         * @access  public
         * @return  null|VectorsCollection
         */
        getVectors: function() {
            var vectors = this._vectors;
            return vectors;
        },

        /**
         * setLoader
         * 
         * @access  public
         * @param   LoaderTriggerComponentView loader
         * @return  Boolean
         */
        setLoader: function(loader) {
            this._loader = loader;
            this._vectors.setLoader(loader);
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseBlockComponentView'], function() {

    /**
     * VectorSetBlockComponentView
     * 
     * @extends BaseBlockComponentView
     */
    window.VectorSetBlockComponentView = BaseBlockComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'VectorSetBlockComponentView')
         */
        _string: 'VectorSetBlockComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        }
    });
});
window.DependencyLoader.push(['BaseFormComponentView'], function() {

    /**
     * AuthBaseFormComponentView
     * 
     * @extends BaseFormComponentView
     */
    window.AuthBaseFormComponentView = BaseFormComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _processingDelay
         * 
         * @access  protected
         * @var     Number (default: 1250)
         */
        _processingDelay: 1250,

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'AuthBaseFormComponentView')
         */
        _string: 'AuthBaseFormComponentView',

        /**
         * _submitSuccessRedirectPath
         * 
         * @access  protected
         * @var     null|String (default: null)
         */
        _submitSuccessRedirectPath: null,

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this.autoFocus();
        },

        /**
         * _getNetworkKey
         * 
         * @access  protected
         * @return  null|String
         */
        _getNetworkKey: function() {
            var name = 'networkKey',
                selector = '[name="data[' + (name) + ']"]',
                $networkKey = this._$element.querySelector(selector);
            if ($networkKey === null) {
                return null;
            }
            var networkKey = $networkKey.value.trim();
            return networkKey;
        },

        /**
         * _handleXHRResolveEvent
         * 
         * @access  protected
         * @param   Object response
         * @return  Boolean
         */
        _handleXHRResolveEvent: function(response) {
            this._super(response);
            var networkKey = this._getNetworkKey(),
                path = this._submitSuccessRedirectPath;
            if (networkKey === 'canva') {
                var method = 'post',
                    payload = this._getPayload();
                RequestUtils.submit(path, method, payload);
                return true;
            }
            window.location.href = path;
            return true;
        }
    });
});
window.DependencyLoader.push(['AuthBaseFormComponentView'], function() {

    /**
     * AuthChangePasswordFormComponentView
     * 
     * @extends AuthBaseFormComponentView
     */
    window.AuthChangePasswordFormComponentView = AuthBaseFormComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'AuthChangePasswordFormComponentView')
         */
        _string: 'AuthChangePasswordFormComponentView',

        /**
         * _submitSuccessRedirectPath
         * 
         * @access  protected
         * @var     null|String (default: '/password/changed')
         */
        _submitSuccessRedirectPath: '/password/changed',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        }
    });
});
window.DependencyLoader.push(['AuthBaseFormComponentView'], function() {

    /**
     * AuthLoginFormComponentView
     * 
     * @extends AuthBaseFormComponentView
     */
    window.AuthLoginFormComponentView = AuthBaseFormComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'AuthLoginFormComponentView')
         */
        _string: 'AuthLoginFormComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this._setSubmitSuccessRedirectPath();
            this._setTimezone();
        },

        /**
         * _setSubmitSuccessRedirectPath
         * 
         * @access  protected
         * @return  Boolean
         */
        _setSubmitSuccessRedirectPath: function() {
            var networkKey = this._getNetworkKey();
            if (networkKey === 'canva') {
                this._submitSuccessRedirectPath = '/integrations/canva/auth/track';
                return true;
            }
            var redirectDestination = RequestUtils.getURLParamValue('redirectPath') || RequestUtils.getURLParamValue('redirectURI') || '/';
            this._submitSuccessRedirectPath = redirectDestination;
            return true;
        },

        /**
         * _setTimezone
         * 
         * @access  protected
         * @return  Boolean
         */
        _setTimezone: function() {
            var $timezone = this.__dataName('timezone');
            if ($timezone === null) {
                return false;
            }
            var timezone = '';
            try {
                timezone = Intl.DateTimeFormat().resolvedOptions().timeZone;
            } catch(err) {}
            $timezone.value = timezone;
            return true;
        }
    });
});
window.DependencyLoader.push(['AuthBaseFormComponentView'], function() {

    /**
     * AuthResetPasswordFormComponentView
     * 
     * @extends AuthBaseFormComponentView
     */
    window.AuthResetPasswordFormComponentView = AuthBaseFormComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _autoFocusSelector
         * 
         * @access  protected
         * @var     null|String (default: '[type="email"]')
         */
        _autoFocusSelector: '[type="email"]',

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'AuthResetPasswordFormComponentView')
         */
        _string: 'AuthResetPasswordFormComponentView',

        /**
         * _submitSuccessRedirectPath
         * 
         * @access  protected
         * @var     null|String (default: '/password/sent')
         */
        _submitSuccessRedirectPath: '/password/sent',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        }
    });
});
window.DependencyLoader.push(['AuthBaseFormComponentView'], function() {

    /**
     * AuthSignupFormComponentView
     * 
     * @extends AuthBaseFormComponentView
     */
    window.AuthSignupFormComponentView = AuthBaseFormComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'AuthSignupFormComponentView')
         */
        _string: 'AuthSignupFormComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this._setSubmitSuccessRedirectPath();
            this._setTimezone();
        },

        /**
         * _setSubmitSuccessRedirectPath
         * 
         * @access  protected
         * @return  Boolean
         */
        _setSubmitSuccessRedirectPath: function() {
            var networkKey = this._getNetworkKey();
            if (networkKey === 'canva') {
                this._submitSuccessRedirectPath = '/integrations/canva/auth/track';
                return true;
            }
            var redirectDestination = RequestUtils.getURLParamValue('redirectPath') || RequestUtils.getURLParamValue('redirectURI') || '/';
            this._submitSuccessRedirectPath = redirectDestination;
            return true;
        },

        /**
         * _setTimezone
         * 
         * @access  protected
         * @return  Boolean
         */
        _setTimezone: function() {
            var $timezone = this.__dataName('timezone');
            if ($timezone === null) {
                return false;
            }
            var timezone = '';
            try {
                timezone = Intl.DateTimeFormat().resolvedOptions().timeZone;
            } catch(err) {}
            $timezone.value = timezone;
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseComponentView'], function() {

    /**
     * BaseFormComponentView
     * 
     * @fires   ready
     * @fires   resolved
     * @extends BaseComponentView
     */
    window.BaseFormComponentView = BaseComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _disabled
         * 
         * @access  protected
         * @var     Boolean (default: false)
         */
        _disabled: false,

        /**
         * _processingDelay
         * 
         * @access  protected
         * @var     null|Number (default: 500)
         */
        _processingDelay: 500,

        /**
         * _events
         * 
         * @access  protected
         * @var     Function
         */
        _events: function() {
            return Object.assign(this._super(), {

                /**
                 * submit
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                submit: function(event, $element) {
                    this._handleSubmitEvent();
                }
            });
        },

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'BaseFormComponentView')
         */
        _string: 'BaseFormComponentView',

        /**
         * _submitEvaluator
         * 
         * @access  protected
         * @var     null|Function (default: null)
         */
        _submitEvaluator: null,

        /**
         * _submitting
         * 
         * @access  protected
         * @var     Boolean (default: false)
         */
        _submitting: false,

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this._addElementsKeyDownEventListeners();
            this._addLabelClickEventListeners();
            // this._addSelectClickEventListeners();
            this._addSubmitEventListener();
            this._addSubmitButtonKeyDownEventListener();
            this._processingDelay = ConfigUtils.getPublicValue('uiux', 'formProcessingDelay');
        },

        /**
         * _addElementsKeyDownEventListeners
         * 
         * Adds enter-key event listeners to relevant inputs associated with the
         * form to ensure the form is submitted.
         * 
         * @access  protected
         * @return  Boolean
         */
        _addElementsKeyDownEventListeners: function() {
            var $elements = this._getElements(),
                handler = this._handleElementKeyDownEvent.bind(this);
            for (var $element of $elements) {
                $element.addEventListener('keydown', function(event) {
                    handler(event);
                });
            }
            return true;
        },

        /**
         * _addLabelClickEventListeners
         * 
         * @access  protected
         * @return  Boolean
         */
        _addLabelClickEventListeners: function() {
            var all = true,
                $elements = this.__find('label', all),
                handler = this._handleLabelClickEvent.bind(this);
            $elements.addEventListener('click', function(event) {
                handler(event);
            });
            return true;
        },

        /**
         * _addSelectClickEventListeners
         * 
         * @access  protected
         * @return  Boolean
         */
        // _addSelectClickEventListeners: function() {
        //     var all = true,
        //         $elements = this.__find('select', all),
        //         handler = this._handleSelectClickEvent.bind(this);
        //     $elements.addEventListener('click', function(event) {
        //         handler(event);
        //     });
        //     return true;
        // },

        /**
         * _addSubmitButtonKeyDownEventListener
         * 
         * Adds space-key event listener to relevant button associated with the
         * form to ensure the form is submitted.
         * 
         * @access  protected
         * @return  Boolean
         */
        _addSubmitButtonKeyDownEventListener: function() {
            var $elements = this.__lookup('submit', true),
                handler = this._handleSubmitButtonKeyDownEvent.bind(this);
            $elements.addEventListener('keydown', handler);
            return true;
        },

        /**
         * _addSubmitEventListener
         * 
         * Adds submit event istener to the form it self so that default
         * behaviour goes through the correct submit flow.
         * 
         * @access  protected
         * @return  Boolean
         */
        _addSubmitEventListener: function() {
            var $element = this._$element,
                handler = this._handleSubmitEvent.bind(this);
            $element.addEventListener('submit', function(event) {
                event.preventDefault();
                handler();
            });
            return true;
        },

        /**
         * _disable
         * 
         * @access  protected
         * @return  Boolean
         */
        _disable: function() {
            ModalUtils.freezeVisible();
            this._disabled = true;
            this._makeElementsReadonly();
            this._disableLabels();
            this._setFormState('processing');
            this._hideErrors();
            document.activeElement.blur();
            return true;
        },

        /**
         * _disableLabels
         * 
         * @access  protected
         * @return  Boolean
         */
        _disableLabels: function() {
            var $labels = this.__find('label', true);
            $labels.disable();
            return true;
        },

        /**
         * _enableLabels
         * 
         * @access  protected
         * @return  Boolean
         */
        _enableLabels: function() {
            var $labels = this.__find('label', true);
            $labels.enable();
            return true;
        },

        /**
         * _getElements
         * 
         * @access  protected
         * @return  HTMLFormControlsCollection
         */
        _getElements: function() {
            var $element = this._$element,
                $elements = $element.elements;
            $elements = Array.from($elements);
            return $elements;
        },

        /**
         * _getFormData
         * 
         * @access  protected
         * @return  FormData
         */
        _getFormData: function() {
            var $form = this._$element,
                formData = new FormData($form);
            formData = this._updateCheckboxFormData(formData);
            return formData;
        },

        /**
         * _getPayload
         * 
         * @access  protected
         * @return  Boolean
         */
        _getPayload: function() {
            var payload = {},
                formData = this._getFormData();
            for(var pair of formData.entries()) {
                var key = pair[0],
                    value = pair[1];
                payload[key] = value;
            }
            return payload;
        },

        /**
         * _handleElementKeyDownEvent
         * 
         * @see     https://sentry.io/organizations/iconduck/issues/3654248790
         * @access  protected
         * @param   Object event
         * @return  Boolean
         */
        _handleElementKeyDownEvent: function(event) {
            if (this._disabled === true) {
                return false;
            }

            // Spacebar check for readonly checkboxes
            var code = event.code || '',
                $target = event.target;
            code = code.toLowerCase();
            if (code === 'space') {
                if ($target.getAttribute('readonly') !== null) {
                    event.preventDefault();
                    return false;
                }
            }

            // If not enter key, bail
            if (code !== 'enter') {
                return false;
            }

            // Handle textarea
            var tagName = $target.tagName || '',
                tagName = tagName.toLowerCase();
            if (tagName === 'textarea') {
                if (event.metaKey === true) {
                    this._handleSubmitEvent();
                    return true;
                }
                return false;
            }
            // if (tagName === 'select') {
            //     return false;
            // }

            // Let's do this!
            this._handleSubmitEvent();
            return true;
        },

        /**
         * _handleLabelClickEvent
         * 
         * @access  protected
         * @param   Object event
         * @return  Boolean
         */
        _handleLabelClickEvent: function(event) {
            var $target = event.target;
            if ($target === null ) {
                return false;
            }
            if ($target === undefined) {
                return false;
            }
            var forAttributeValue = $target.getAttribute('for');
            if (forAttributeValue === null) {
                return false;
            }
            var $element = this.__id(forAttributeValue);
            if ($element === null) {
                return false;
            }
            if ($element.readOnly === true) {
                event.preventDefault();
                return true;
            }
            return true;
        },

        /**
         * _handleSelectClickEvent
         * 
         * @access  protected
         * @param   Object event
         * @return  Boolean
         */
        // _handleSelectClickEvent: function(event) {
        //     var $target = event.target;
        //     if ($target === null ) {
        //         return false;
        //     }
        //     if ($target === undefined) {
        //         return false;
        //     }
        //     if ($target.getAttribute('readonly') === null) {
        //         return false;
        //     }
        //     if ($target.getAttribute('readonly') === undefined) {
        //         return false;
        //     }
        //     if ($target.getAttribute('readonly').toInt() === 1) {
        //         // event.preventDefault();
        //         $target.blur();
        //         window.focus();
        //         return true;
        //     }
        //     return true;
        // },

        /**
         * _handleSubmitButtonKeyDownEvent
         * 
         * @see     https://sentry.io/organizations/iconduck/issues/3654248790
         * @access  protected
         * @param   Object event
         * @return  Boolean
         */
        _handleSubmitButtonKeyDownEvent: function(event) {
            var code = event.code || '';
            code = code.toLowerCase();
            if (code === 'space') {
                // event.preventDefault();
                this._handleSubmitEvent();
            }
            return true;
        },

        /**
         * _handleSubmitEvent
         * 
         * @access  protected
         * @return  Boolean
         */
        _handleSubmitEvent: function() {
            if (this._submitting === true) {
                return false;
            }
            if (this._validSubmitAttempt() === false) {
                return false;
            }
            this._triggerReadyCustomEvent();
            this._submitting = true;
            this._disable();
            var request = this._processSubmitRequest.bind(this),
                delay = this._processingDelay;
            if (delay === null) {
                request();
                return true;
            }
            DataUtils.delay(delay).then(request);
            return true;
        },

        /**
         * _handleXHRRejectEvent
         * 
         * @access  protected
         * @param   Object response
         * @return  Boolean
         */
        _handleXHRRejectEvent: function(response) {
            this._submitting = false;
            if (response instanceof Error) {
                throw response;
            }
            var errors = response.errors || [];
            this.enable();
            this._showErrors(errors);
            return true;
        },

        /**
         * _handleXHRResolveEvent
         * 
         * @access  protected
         * @param   Object response
         * @return  Boolean
         */
        _handleXHRResolveEvent: function(response) {
            this._submitting = false;
            this._setFormState('success');
            var args = [this, response];
            this.triggerCustomEvent('resolved', args);
            return true;
        },

        /**
         * _hideErrors
         * 
         * @access  protected
         * @return  Boolean
         */
        _hideErrors: function() {
            var $element = this.__find('div.errors');
            if ($element === null) {
                return false;
            }
            $element.addClass('display-none');
            return true;
        },

        /**
         * _makeElementsReadonly
         * 
         * @access  protected
         * @return  void
         */
        _makeElementsReadonly: function() {
            var $elements = this._getElements();
            $elements.readonly(true);
        },

        /**
         * _makeElementsWriteable
         * 
         * @access  protected
         * @return  void
         */
        _makeElementsWriteable: function() {
            var $elements = this._getElements();
            for (var $element of $elements) {
                if ($element.getAttribute('data-readonly') === null) {
                    $element.readonly(false);
                }
            }
        },

        /**
         * _processSubmitRequest
         * 
         * @access  protected
         * @return  Promise
         */
        _processSubmitRequest: function() {
            var xhr = this._$element.getAttribute('data-component-xhr');
            if (xhr === null) {
                var promise = this._processSubmitXHRRequest();
                return promise;
            }
            xhr = xhr.toInt();
            if (xhr === 1) {
                var promise = this._processSubmitXHRRequest();
                return promise;
            }
            var promise = this._processSubmitSyncRequest();
            return promise;
        },

        /**
         * _processSubmitSyncRequest
         * 
         * @access  protected
         * @return  Promise
         */
        _processSubmitSyncRequest: function() {
            var path = this._$element.getAttribute('action'),
                method = this._$element.getAttribute('method'),
                data = this._getPayload(),
                promise = RequestUtils.submit(path, method, data);
            return promise;
        },

        /**
         * _processSubmitXHRRequest
         * 
         * @access  protected
         * @return  Promise
         */
        _processSubmitXHRRequest: function() {
            var $form = this._$element,
                method = $form.getAttribute('method') || 'get',
                path = $form.getAttribute('action'),
                data = {},
                options = {};
            options.formData = this._getFormData();
            var request = RequestUtils[method](path, data, options),
                resolve = this._handleXHRResolveEvent.bind(this),
                reject = this._handleXHRRejectEvent.bind(this),
                promise = request.then(resolve).catch(reject);
            return promise;
        },

        /**
         * _showError
         * 
         * @see     https://i.imgur.com/s0dMhdd.jpg
         * @access  protected
         * @param   Object error
         * @return  Boolean
         */
        _showError: function(error) {
            var $errors = this.__find('div.errors'),
                $error = this.__find('div.errors div.error');
            if ($errors === null || $error === null) {
                return false;
            }
            var inputName = error.meta.input,
                selector = '[name="' + (inputName) + '"]',
                $input = this.__find(selector);
            $errors.removeClass('display-none');
            $error.innerHTML = error.title || 'Something went wrong. Please reload the page.';
            this._setFormState('error');
            if ($input !== null) {
                $input.focus();
                $input.select && $input.select();
            }
            return true;
        },

        /**
         * _showErrors
         * 
         * @access  protected
         * @param   Array errors
         * @return  Boolean
         */
        _showErrors: function(errors) {
            if (errors.length === 0) {
                return false;
            }
            var error = errors[0],
                shown = this._showError(error);
            return shown;
        },

        /**
         * _triggerReadyCustomEvent
         * 
         * @access  protected
         * @return  Boolean
         */
        _triggerReadyCustomEvent: function() {
            var args = [this];
            this.triggerCustomEvent('ready', args);
            return true;
        },

        /**
         * _updateCheckboxFormData
         * 
         * @access  protected
         * @param   FormData formData
         * @return  FormData
         */
        _updateCheckboxFormData: function(formData) {
            var $checkboxes = this.__find('[type="checkbox"]', true),
                formDataNames = [];
            for (var pair of formData.entries()) {
                var name = pair[0];
                formDataNames.push(name);
            }
            for (var $checkbox of $checkboxes) {
                var name = $checkbox.getAttribute('name'),
                    includes = formDataNames.includes(name);
                if (includes === false) {
                    formData.append(name, '0');
                }
            }
            return formData;
        },

        /**
         * _validSubmitAttempt
         * 
         * @access  protected
         * @return  Boolean
         */
        _validSubmitAttempt: function() {
            var submitEvaluator = this._submitEvaluator;
            if (submitEvaluator === null) {
                return true;
            }
            var response = submitEvaluator();
            if (response === false) {
                return false;
            }
            return true;
        },

        /**
         * enable
         * 
         * @access  public
         * @return  Boolean
         */
        enable: function() {
            ModalUtils.unfreezeVisible();
            this._disabled = false;
            this._makeElementsWriteable();
            this._enableLabels();
            this._setFormState('idle');
            // this._hideErrors();
            // document.activeElement.blur();
            return true;
        },

        /**
         * setDisabled
         * 
         * @access  public
         * @param   Boolean value
         * @return  Boolean
         */
        setDisabled: function(value) {
            this._disabled = value;
            return true;
        },

        /**
         * setProcessingDelay
         * 
         * @access  public
         * @param   null|Number delay
         * @return  Boolean
         */
        setProcessingDelay: function(delay) {
            this._processingDelay = delay;
            return true;
        },

        /**
         * setSubmitEvaluator
         * 
         * @access  public
         * @param   Function submitEvaluator
         * @return  Boolean
         */
        setSubmitEvaluator: function(submitEvaluator) {
            this._submitEvaluator = submitEvaluator;
            return true;
        },

        /**
         * setXHRRejectEventHandler
         * 
         * @access  public
         * @param   Function handler
         * @return  Boolean
         */
        setXHRRejectEventHandler: function(handler) {
            this._handleXHRRejectEvent = handler;
            return true;
        },

        /**
         * setXHRResolveEventHandler
         * 
         * @access  public
         * @param   Function handler
         * @return  Boolean
         */
        setXHRResolveEventHandler: function(handler) {
            this._handleXHRResolveEvent = handler;
            return true;
        },

        /**
         * submit
         * 
         * @access  public
         * @return  Boolean
         */
        submit: function() {
            var response = this._handleSubmitEvent();
            return response;
        }
    });
});
window.DependencyLoader.push(['BaseComponentView'], function() {

    /**
     * ChipComponentView
     * 
     * @extends BaseComponentView
     */
    window.ChipComponentView = BaseComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'ChipComponentView')
         */
        _string: 'ChipComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this._addDeleteEventListener();
        },

        /**
         * _addDeleteEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addDeleteEventListener: function() {
            var trigger = this.getComponent('DELETERequestTrigger'),
                handler = this._handleDeleteEvent.bind(this);
            trigger.addCustomEventListenerOnce('request/resolved', handler);
            return true;
        },

        /**
         * _handleDeleteEvent
         * 
         * @access  protected
         * @return  Boolean
         */
        _handleDeleteEvent: function() {
            this.destroy();
            return true;
        },
    });
});
window.DependencyLoader.push(['BaseModalComponentView'], function() {

    /**
     * AddCollectionItemsModalComponentView
     * 
     * @see     https://i.imgur.com/KK7J5Ny.jpg
     * @extends BaseModalComponentView
     */
    window.AddCollectionItemsModalComponentView = BaseModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _collectionRowBlocks
         * 
         * @access  protected
         * @var     Object (default: {})
         */
        _collectionRowBlocks: {},

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'AddCollectionItemsModalComponentView')
         */
        _string: 'AddCollectionItemsModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this._addCollectionEventListeners();
            this._drawCollectionRows();
            this._sortCollectionRows();
            this._showHideCollections();
        },

        /**
         * destroy
         * 
         * @access  public
         * @return  Boolean
         */
        destroy: function() {
            var collectionRowBlocks = this._collectionRowBlocks,
                keys = Object.keys(collectionRowBlocks);
            for (var key of keys) {
                this._collectionRowBlocks[key].destroy();
            }
            var collections = this._getCollections();
            collections.clearCustomEventListeners();
            this._super();
            return true;
        },

        /**
         * _addCollectionEventListeners
         * 
         * @access  protected
         * @return  Boolean
         */
        _addCollectionEventListeners: function() {
            this._addCollectionsAddEventListener();
            this._addCollectionsRemoveEventListener();
            return true;
        },

        /**
         * _addCollectionsAddEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addCollectionsAddEventListener: function() {
            var collections = this._getCollections(),
                handler = this._handleCollectionsAddEvent.bind(this);
            collections.addCustomEventListener('add', handler);
            return true;
        },

        /**
         * _addCollectionsRemoveEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addCollectionsRemoveEventListener: function() {
            var collections = this._getCollections(),
                handler = this._handleCollectionsRemoveEvent.bind(this);
            collections.addCustomEventListener('remove', handler);
            return true;
        },

        /**
         * _drawCollectionRow
         * 
         * @access  protected
         * @param   CollectionActiveRecord collection
         * @return  CollectionRowBlockComponentView
         */
        _drawCollectionRow: function(collection) {

            // Data
            var data = {};
            data.collection = collection;
            data.vector = this._data.vector;

            // Draw it
            var templateName = 'CollectionRowBlockComponent',
                $row = ElementUtils.renderTemplate(templateName, data),
                $parent = this.__find('.collections');
            $parent.prepend($row);

            // Tracking
            var publicId = collection.get('publicId'),
                view = $row.getView();
            this._collectionRowBlocks[publicId] = view;
            return view;
        },

        /**
         * _drawCollectionRows
         * 
         * @access  protected
         * @return  Boolean
         */
        _drawCollectionRows: function() {
            var collections = this._getCollections(),
                collections = collections.created();
            for (var collection of collections) {
                this._drawCollectionRow(collection);
            }
            return true;
        },

        /**
         * _sortCollectionRows
         * 
         * @access  protected
         * @return  Boolean
         */
        _sortCollectionRows: function() {
            var collections = this._getCollections(),
                collections = collections.created().sort(DataUtils.sort.bind(DataUtils, 'name')).reverse();
            for (var collection of collections) {
                var publicId = collection.get('publicId'),
                    collectionRowBlock = this._collectionRowBlocks[publicId],
                    $collectionRowBlock = collectionRowBlock.getElement();
                $collectionRowBlock.parentNode.prepend($collectionRowBlock);
            }
            return true;
        },

        /**
         * _getCollections
         * 
         * @access  protected
         * @return  CollectionsCollection
         */
        _getCollections: function() {
            var user = AuthUtils.getUser(),
                collections = user.getCollections();
            return collections;
        },

        /**
         * _handleCollectionsAddEvent
         * 
         * @see     https://developer.mozilla.org/en-US/docs/Web/API/Element/scrollIntoView
         * @see     https://stackoverflow.com/questions/62098093/scroll-behaviour-smooth-not-working-at-all
         * @access  protected
         * @param   CollectionActiveRecord collection
         * @return  Boolean
         */
        _handleCollectionsAddEvent: function(collection) {
            var collectionRow = this._drawCollectionRow(collection);
            this._showHideCollections();
            this._sortCollectionRows();
            collectionRow.scrollIntoView();
            collection.add(this._data.vector);
            // setTimeout(function() {
            //     $collectionRow.classList.add('collection_row_block-pulse');
            // }, 150);
            // setTimeout(function() {
            //     $collectionRow.classList.remove('collection_row_block-pulse');
            // }, (800 + 800 + (800 / 2)));
            return true;
        },

        /**
         * _handleCollectionsRemoveEvent
         * 
         * @access  protected
         * @param   CollectionActiveRecord collection
         * @return  Boolean
         */
        _handleCollectionsRemoveEvent: function(collection) {
            this._removeCollectionRow(collection);
            this._showHideCollections();
            return true;
        },

        /**
         * _removeCollectionRow
         * 
         * @access  protected
         * @param   CollectionActiveRecord collection
         * @return  Boolean
         */
        _removeCollectionRow: function(collection) {
            var publicId = collection.get('publicId'),
                collectionRowBlock = this._collectionRowBlocks[publicId];
            collectionRowBlock.destroy();
            return true;
        },

        /**
         * _showHideCollections
         * 
         * @access  protected
         * @return  Boolean
         */
        _showHideCollections: function() {
            var $empty = this.__find('.empty'),
                $collections = this.__find('.collections'),
                collections = this._getCollections().created();
            if (collections.length === 0) {
                $empty.removeClass('display-none');
                $collections.addClass('display-none');
                return true;
            }
            $empty.addClass('display-none');
            $collections.removeClass('display-none');
            return true;
        },

        /**
         * _scrollFirstIntoView
         * 
         * @access  protected
         * @return  Boolean
         */
        _scrollFirstIntoView: function() {
            var collectionRowBlocks = this._collectionRowBlocks,
                keys = Object.keys(collectionRowBlocks);
            if (keys.length === 0) {
                return false;
            }
            var $selected = this.__find('[data-component-name="CollectionRowBlock"][data-state="selected"]');
            if ($selected === null) {
                return false;
            }
            var firstCollectionRowBlock = $selected.data.view;
            firstCollectionRowBlock.scrollIntoView();
            return true;
        },

        /**
         * show
         * 
         * @access  public
         * @return  Boolean
         */
        show: function() {
            var response = this._super();
            if (response === false) {
                return false;
            }
            this._scrollFirstIntoView();
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseModalComponentView', 'FormModalComponentView'], function() {

    /**
     * AddVectorSetVectorsModalComponentView
     * 
     * @see     https://transloadit.com/docs/api/rate-limiting/
     * @extends FormModalComponentView
     */
    window.AddVectorSetVectorsModalComponentView = FormModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'AddVectorSetVectorsModalComponentView')
         */
        _string: 'AddVectorSetVectorsModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this._addChooseFilesClickEventListener();
        },

        /**
         * _addChooseFilesClickEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addChooseFilesClickEventListener: function() {
            var $chooseFiles = this.__lookup('chooseFiles'),
                handler = this._handleChooseFilesClickEvent.bind(this);
            $chooseFiles.addEventListener('click', handler);
            return true;
        },

        /**
         * _getUppyOptions
         * 
         * @access  protected
         * @return  Object
         */
        _getUppyOptions: function() {
            var allowedFileTypes = [
                    'application/zip',
                ],
                callback = this._receiveUppyPayloads.bind(this),
                maxFileSize = 100 * 1024 * 1024,
                maxNumberOfFiles = 10,
                sources = [],
                options = {
                    allowedFileTypes: allowedFileTypes,
                    callback: callback,
                    maxFileSize: maxFileSize,
                    maxNumberOfFiles: maxNumberOfFiles,
                    sources: sources,
                    steps: this._getUppyTransloaditAssemblySteps(),
                    waitForEncoding: true
                };
            return options;
        },

        /**
         * _getUppyTransloaditAssemblySteps
         * 
         * Returns an object defining what operations should be performed
         * against any uploaded files.
         * 
         * @see     https://i.imgur.com/TgwfU2W.jpg
         * @see     https://transloadit.com/c/iconduck/templates/my-template-1665683601589
         * @note    The keys in the object below are both special and reserved,
         *          as well as keys that can be used in subsequent steps.
         * @access  protected
         * @return  Object
         */
        _getUppyTransloaditAssemblySteps: function() {
            var steps = {
                ':original': {
                    'robot': '/upload/handle',
                },
                'action:decompress-archive': {
                    'use': ':original',
                    'robot': '/file/decompress'
                },
                'action:deliver': {
                    'use': 'action:decompress-archive',
                    'robot': '/file/filter',
                    'accepts': [
                        [
                            '${file.mime}',
                            'regex',
                            'svg'
                        ],
                        [
                            '${file.mime}',
                            'regex',
                            'xml'
                        ],
                        [
                            '${file.mime}',
                            'regex',
                            'plain'
                        ]
                    ],
                }
            };
            return steps;
        },

        /**
         * _handleChooseFilesClickEvent
         * 
         * @access  protected
         * @param   Object event
         * @return  Boolean
         */
        _handleChooseFilesClickEvent: function(event) {
            event.preventDefault();
            this._openUppy();
            return true;
        },

        /**
         * _handleFormResolvedEvent
         * 
         * @access  protected
         * @param   BaseFormComponentView form
         * @param   Object response
         * @return  Boolean
         */
        _handleFormResolvedEvent: function(form, response) {
            this._showSuccessModal();
            this._resetUI();
            return true;
        },

        /**
         * _openUppy
         * 
         * @access  protected
         * @return  Boolean
         */
        _openUppy: function() {
            var clientWrapper = new UppyClientWrapper(),
                options = this._getUppyOptions(),
                uppyCore = clientWrapper.getClient(options);
            if (uppyCore === null) {
                return false;
            }
            uppyCore.getPlugin('Dashboard').openModal();
            return true;
        },

        /**
         * _receiveUppyPayloads
         * 
         * @access  protected
         * @param   Array payloads
         * @return  Boolean
         */
        _receiveUppyPayloads: function(payloads) {
            if (payloads.length === 0) {
                return false;
            }
            for (var payload of payloads) {
                delete payload.meta;
            }
            this.__dataName('payloads').value = JSON.stringify(payloads);
            var form = this._getForm();
            form.enable();
            this.__find('[data-click="submit"]').enable();
            var $summary = this.__find('div.summary'),
                $count = this.__lookup('count');
            $summary.removeClass('display-none');
            $count.innerText = (payloads.length) + ' vectors';
            return true;
        },

        /**
         * _resetUI
         * 
         * @access  protected
         * @return  Boolean
         */
        _resetUI: function() {
            var form = this._getForm();
            form.enable();
            var $summary = this.__find('div.summary');
            $summary.addClass('display-none');
            this.__lookup('submit').disable();
            form.setDisabled(true);
            return true;
        },
    
        /**
         * _showSuccessModal
         * 
         * @access  protected
         * @return  Boolean
         */
        _showSuccessModal: function() {
            var primary = 'Vectors imported!',
                secondary = 'Cron jobs will take care of the rest.';
            ModalUtils.showSuccess(primary, secondary);
            if (UserAgentUtils.focused() === false) {
                AudioUtils.play('duck-quack-01.mp3');
            }
            return true;
        },
    });
});
window.DependencyLoader.push(['BaseModalComponentView', 'FormModalComponentView'], function() {

    /**
     * BlockUserModalComponentView
     * 
     * @extends FormModalComponentView
     */
    window.BlockUserModalComponentView = FormModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'BlockUserModalComponentView')
         */
        _string: 'BlockUserModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * _handleFormResolvedEvent
         * 
         * @access  protected
         * @param   BaseFormComponentView form
         * @param   Object response
         * @return  Boolean
         */
        _handleFormResolvedEvent: function(form, response) {
            this._super();
            var primary = 'Email address blocked',
                secondary = 'They can no longer use login or password reset experiences.';
            ModalUtils.showSuccess(primary, secondary);
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseModalComponentView', 'FormModalComponentView'], function() {

    /**
     * CreateVectorSetDesignerModalComponentView
     * 
     * @extends FormModalComponentView
     */
    window.CreateVectorSetDesignerModalComponentView = FormModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'CreateVectorSetDesignerModalComponentView')
         */
        _string: 'CreateVectorSetDesignerModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * _handleFormResolvedEvent
         * 
         * @access  protected
         * @param   BaseFormComponentView form
         * @param   Object response
         * @return  Boolean
         */
        _handleFormResolvedEvent: function(form, response) {
            this._super(form, response);
            var vectorSet = this._data.activeRecord,
                vectorSetDesigners = vectorSet.getVectorSetDesigners(),
                publicData = response.data.object,
                model = vectorSetDesigners.model(),
                vectorSetDesigner = model.setActiveRecord(publicData),
                args = [vectorSetDesigner];
            vectorSetDesigners.add(vectorSetDesigner);
            this.triggerCustomEvent('form/resolved', args);
            this.destroy();
            var modalKey = 'ManageVectorSetDesigners',
                modal = ModalUtils.getModal(modalKey);
            modal.destroy();
            ModalUtils.showManageVectorSetDesigners(vectorSet);
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseModalComponentView', 'FormModalComponentView'], function() {

    /**
     * CreateVectorSetSubsetModalComponentView
     * 
     * @extends FormModalComponentView
     */
    window.CreateVectorSetSubsetModalComponentView = FormModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'CreateVectorSetSubsetModalComponentView')
         */
        _string: 'CreateVectorSetSubsetModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * _handleFormResolvedEvent
         * 
         * @access  protected
         * @param   BaseFormComponentView form
         * @param   Object response
         * @return  Boolean
         */
        _handleFormResolvedEvent: function(form, response) {
            this._super(form, response);
            var vectorSet = this._data.activeRecord,
                vectorSetSubsets = vectorSet.getVectorSetSubsets(),
                publicData = response.data.object,
                model = vectorSetSubsets.model(),
                vectorSetSubset = model.setActiveRecord(publicData),
                args = [vectorSetSubset];
            vectorSetSubsets.add(vectorSetSubset);
            this.triggerCustomEvent('form/resolved', args);
            this.destroy();
            var modalKey = 'ManageVectorSetSubsets',
                modal = ModalUtils.getModal(modalKey);
            modal.destroy();
            ModalUtils.showManageVectorSetSubsets(vectorSet);
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseModalComponentView', 'FormModalComponentView'], function() {

    /**
     * ImportVectorModalComponentView
     * 
     * @extends FormModalComponentView
     */
    window.ImportVectorModalComponentView = FormModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'ImportVectorModalComponentView')
         */
        _string: 'ImportVectorModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        }
    });
});
window.DependencyLoader.push(['BaseModalComponentView'], function() {

    /**
     * ManageVectorSetDesignersModalComponentView
     * 
     * @extends BaseModalComponentView
     */
    window.ManageVectorSetDesignersModalComponentView = BaseModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'ManageVectorSetDesignersModalComponentView')
         */
        _string: 'ManageVectorSetDesignersModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        }
    });
});
window.DependencyLoader.push(['BaseModalComponentView'], function() {

    /**
     * ManageVectorSetSubsetsModalComponentView
     * 
     * @extends BaseModalComponentView
     */
    window.ManageVectorSetSubsetsModalComponentView = BaseModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'ManageVectorSetSubsetsModalComponentView')
         */
        _string: 'ManageVectorSetSubsetsModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        }
    });
});
window.DependencyLoader.push(['BaseModalComponentView', 'FormModalComponentView'], function() {

    /**
     * QueryVectorSetVectorsModalComponentView
     * 
     * @extends FormModalComponentView
     */
    window.QueryVectorSetVectorsModalComponentView = FormModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _events
         * 
         * @access  protected
         * @var     Function
         */
        _events: function() {
            return Object.assign(this._super(), {

                /**
                 * run
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                run: function(event, $element) {
                    this._run();
                },

                /**
                 * test
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                test: function(event, $element) {
                    this._test();
                }
            });
        },

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'QueryVectorSetVectorsModalComponentView')
         */
        _string: 'QueryVectorSetVectorsModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * _drawVectorRows
         * 
         * @access  protected
         * @param   Array vectors
         * @return  Boolean
         */
        _drawVectorRows: function(vectors) {
            this._emptySubsetVectorRows();
            var templateName = 'QueryVectorSetVectorRowBlockComponent',
                data = {};
            for (var vector of vectors) {
                var publicId = vector.publicId,
                    name = 'Vector',
                    publicData = vector;
                data.vector = FrameworkUtils.setActiveRecord(publicId, name, publicData);
                var $row = ElementUtils.renderTemplate(templateName, data),
                    $parent = this.__find('.subset');
                $parent.append($row);
            }
            return true;
        },

        /**
         * _emptySubsetVectorRows
         * 
         * @access  protected
         * @return  Boolean
         */
        _emptySubsetVectorRows: function() {
            var $parent = this.__find('.subset'),
                $children = Array.prototype.slice.call($parent.childNodes);
            $children.forEach(function($child) {
                $child.parentNode.removeChild($child);
            });
            return true;
        },

        /**
         * _enabledRunButton
         * 
         * @access  protected
         * @return  Boolean
         */
        _enabledRunButton: function() {
            var selector = '[data-lookup="run"]',
                $button = this.__find(selector);
            $button.enable();
            return true;
        },

        /**
         * _handleFormRunResolvedEvent
         * 
         * @access  protected
         * @param   BaseFormComponentView form
         * @param   Object response
         * @return  Boolean
         */
        _handleFormRunResolvedEvent: function(form, response) {
            // ModalUtils.closeLastVisible();
            var count = response.data.count,
                primary = '' + count.toLocaleString() + ' records affected',
                secondary = 'You may need to reload the page to see changes.';
            ModalUtils.showSuccess(primary, secondary);
            return true;
        },

        /**
         * _handleFormTestResolvedEvent
         * 
         * @access  protected
         * @param   BaseFormComponentView form
         * @param   Object response
         * @return  Boolean
         */
        _handleFormTestResolvedEvent: function(form, response) {
            var $count = this.__lookup('count'),
                count = response.data.count,
                $summary = this.__find('.summary.highlight'),
                vectors = response.data.vectors;
            $count.innerText = count.toLocaleString();
            $summary.removeClass('display-none');
            this._drawVectorRows(vectors);
            return true;
        },

        /**
         * _handleRunEvent
         * 
         * @access  protected
         * @return  Boolean
         */
        _handleRunEvent: function() {
            var form = this._getForm(),
                $form = form.getElement(),
                vectorSet = this._data.vectorSet,
                action = '/vectorSets/' + vectorSet.get('publicId') + '/queries/run';
            $form.setAttribute('action', action);
            form._setFormState('processing');
            var handler = this._handleFormRunResolvedEvent.bind(this);
            form.addCustomEventListenerOnce('resolved', handler);
            form.submit();
            return true;
        },

        /**
         * _handleTestEvent
         * 
         * @access  protected
         * @return  Boolean
         */
        _handleTestEvent: function() {
            var form = this._getForm(),
                $form = form.getElement(),
                vectorSet = this._data.vectorSet,
                action = '/vectorSets/' + vectorSet.get('publicId') + '/queries/test';
            $form.setAttribute('action', action);
            form._setFormState('processing');
            var handler = this._handleFormTestResolvedEvent.bind(this);
            form.addCustomEventListenerOnce('resolved', handler);
            form.submit();
            this._enabledRunButton();
            return true;
        },

        /**
         * _run
         * 
         * @access  protected
         * @return  Boolean
         */
        _run: function() {
            var primary = 'Are you sure?',
                secondary = 'This cannot be undone.',
                handler = this._handleRunEvent.bind(this);
            UserAgentUtils.confirm(primary, secondary).then(handler);
            return true;
        },

        /**
         * _test
         * 
         * @access  protected
         * @return  Boolean
         */
        _test: function() {
            this._handleTestEvent();
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseModalComponentView'], function() {

    /**
     * AlertModalComponentView
     * 
     * @extends BaseModalComponentView
     */
    window.AlertModalComponentView = BaseModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'AlertModalComponentView')
         */
        _string: 'AlertModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        }
    });
});
window.DependencyLoader.push(['BaseModalComponentView'], function() {

    /**
     * APIModalComponentView
     * 
     * @extends BaseModalComponentView
     */
    window.APIModalComponentView = BaseModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _events
         * 
         * @access  protected
         * @var     Function
         */
        _events: function() {
            return Object.assign(this._super(), {

                /**
                 * openMailToTab
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                openMailToTab: function(event, $element) {
                    this._handleRequestAccessClickEvent();
                    this.destroy();
                }
            });
        },

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'APIModalComponentView')
         */
        _string: 'APIModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * _handleRequestAccessClickEvent
         * 
         * @access  protected
         * @return  void
         */
        _handleRequestAccessClickEvent: function() {
            var destination = 'mailto:api@iconduck.com';
            window.open(destination);
            this.destroy();
        },
    });
});
window.DependencyLoader.push(['BaseModalComponentView'], function() {

    /**
     * AuthModalComponentView
     * 
     * @extends BaseModalComponentView
     */
    window.AuthModalComponentView = BaseModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _events
         * 
         * @access  protected
         * @var     Function
         */
        _events: function() {
            return Object.assign(this._super(), {

                /**
                 * showLoginState
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                showLoginState: function(event, $element) {
                    this._setState('login');
                },

                /**
                 * showPasswordState
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                showPasswordState: function(event, $element) {
                    this._setState('password');
                },

                /**
                 * showSignupState
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                showSignupState: function(event, $element) {
                    this._setState('signup');
                }
            })
        },

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'AuthModalComponentView')
         */
        _string: 'AuthModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this._addStateChangeEventListener();
            this._setState('login');
        },

        /**
         * _addStateChangeEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addStateChangeEventListener: function() {
            var handler = this._handleStateChangeEvent.bind(this);
            this.addCustomEventListener('state/change', handler)
            return true;
        },

        /**
         * _handleStateChangeEvent
         * 
         * @access  protected
         * @param   String stateKey
         * @return  Boolean
         */
        _handleStateChangeEvent: function(stateKey) {
            var $links = this.__find('div.links div.link a', true);
            $links.removeClass('active');
            var $active = this.__lookup(stateKey);
            $active.addClass('active');
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseModalComponentView'], function() {

    /**
     * AuthPromptModalComponentView
     * 
     * @extends BaseModalComponentView
     */
    window.AuthPromptModalComponentView = BaseModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'AuthPromptModalComponentView')
         */
        _string: 'AuthPromptModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        }
    });
});
window.DependencyLoader.push(['BaseComponentView'], function() {

    /**
     * BaseModalComponentView
     * 
     * @fires   destroy
     * @extends BaseComponentView
     */
    window.BaseModalComponentView = BaseComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _events
         * 
         * @access  protected
         * @var     Function
         */
        _events: function() {
            return Object.assign(this._super(), {

                /**
                 * destroy
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                destroy: function(event, $element) {
                    this._handleDestroyEvent();
                }
            });
        },

        /**
         * _keyboardShortcutEscapable
         * 
         * @access  protected
         * @var     Boolean (default: true)
         */
        _keyboardShortcutEscapable: true,

        /**
         * _overlayClickEscapable
         * 
         * @access  protected
         * @var     Boolean (default: true)
         */
        _overlayClickEscapable: true,

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'BaseModalComponentView')
         */
        _string: 'BaseModalComponentView',

        /**
         * _visible
         * 
         * @access  protected
         * @var     Boolean (default: false)
         */
        _visible: false,

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this._setupUIModifiers();
        },

        /**
         * _getTabindexPartialSelector
         * 
         * @access  protected
         * @return  String
         */
        _getTabindexPartialSelector: function() {
            var selectors = [];
            selectors.push('[tabindex]');
            selectors.push('a');
            selectors.push('button');
            selectors.push('iframe');
            selectors.push('input:not([type="hidden"])');
            selectors.push('select');
            selectors.push('textarea');
            var selector = selectors.join(',');
            return selector;
        },

        /**
         * _handleDestroyEvent
         * 
         * @access  protected
         * @param   Object event
         * @return  Boolean
         */
        _handleDestroyEvent: function(event) {
            this.destroy();
            return true;
        },

        /**
         * _overrideTabindexes
         * 
         * @access  protected
         * @return  Boolean
         */
        _overrideTabindexes: function() {

            // Selectors
            var selector = this._getTabindexPartialSelector(),
                $elements = document.querySelectorAll(selector);

            // Remove any possible tabindex value
            for (var $element of $elements) {
                if ($element.getAttribute('data-old-tabindex') !== null) {
                    continue;
                }
                var tabindexValue = $element.getAttribute('tabindex');
                if (tabindexValue !== null) {
                    $element.setAttribute('data-old-tabindex', tabindexValue);
                }
                $element.setAttribute('tabindex', '-666');
            }

            // Set
            var $elements = this.__find(selector, true);
            for (var index in $elements) {
                var $element = $elements[index];
                $element.setAttribute('tabindex', index.toInt() + 1);
            }

            // Done
            return true;
        },

        /**
         * _resetTabindexes
         * 
         * @access  protected
         * @return  Boolean
         */
        _resetTabindexes: function() {
            var $elements = document.querySelectorAll('[tabindex="-666"]');
            for (var $element of $elements) {
                $element.removeAttribute('tabindex');
                var oldTabindexValue = $element.getAttribute('data-old-tabindex');
                if (oldTabindexValue !== null) {
                    $element.setAttribute('tabindex', oldTabindexValue);
                    $element.removeAttribute('data-old-tabindex');
                }
            }
            return true;
        },

        /**
         * _setupUIModifiers
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupUIModifiers: function() {
            var helper = this._getHelper('ModalUIModifier');
            helper.set('view', this);
            helper.setup();
            helper.refreshUIModifierAttribute();
            return true;
        },

        /**
         * _validElementHideKeyboardEvent
         * 
         * @access  protected
         * @param   Event event
         * @return  Boolean
         */
        _validElementHideKeyboardEvent: function(event) {
            if (this._keyboardShortcutEscapable === false) {
                return false;
            }
            if (this._frozen === true) {
                return false;
            }
            var response = this._super(event);
            return response;
        },

        /**
         * _validElementHidePointerEvent
         * 
         * @access  protected
         * @param   Event event
         * @return  Boolean
         */
        _validElementHidePointerEvent: function(event) {
            if (this._overlayClickEscapable === false) {
                return false;
            }
            if (this._frozen === true) {
                return false;
            }
            var response = this._super(event);
            if (response === true) {
                return true;
            }
            var $element = this._$element,
                $triggerElement = event.target;
            if ($triggerElement === $element) {
                return true;
            }
            return false;
        },

        /**
         * destroy
         * 
         * @access  public
         * @param   undefined|Object options (default: {})
         * @return  Boolean
         */
        destroy: function(options) {
            options = options || {};
            this.triggerCustomEvent('destroy');
            this._super();
            this.hide(options);
            return true;
        },

        /**
         * escapable
         * 
         * @access  public
         * @return  Boolean
         */
        escapable: function() {
            if (this._keyboardShortcutEscapable === false) {
                return false;
            }
            if (this._overlayClickEscapable === false) {
                return false;
            }
            return true;
        },

        /**
         * hide
         * 
         * @access  public
         * @param   undefined|Object options (default: {})
         * @return  Boolean
         */
        hide: function(options) {
            if (this._visible === false) {
                return false;
            }
            tippy.hideAll({duration: 0});
            ElementHideStackUtils.remove(this);
            this._resetTabindexes();
            this._visible = false;
            this._addHiddenClass();
            return true;
        },

        /**
         * freeze
         * 
         * @access  public
         * @return  Boolean
         */
        freeze: function() {
            var frozen = this._frozen;
            if (frozen === true) {
                return false;
            }
            this._$element.addClass('frozen');
            this._frozen = true;
            return true;
        },

        /**
         * frozen
         * 
         * @access  public
         * @return  Boolean
         */
        frozen: function() {
            var frozen = this._frozen;
            return frozen;
        },

        /**
         * show
         * 
         * @access  public
         * @return  Boolean
         */
        show: function() {
            if (this._visible === true) {
                return false;
            }
            ElementHideStackUtils.push(this, this.destroy);
            this._overrideTabindexes();
            document.activeElement.blur();
            this._visible = true;
            this._removeHiddenClass();
            this.autoFocus();
            return true;
        },

        /**
         * unfreeze
         * 
         * @access  public
         * @return  Boolean
         */
        unfreeze: function() {
            var frozen = this._frozen;
            if (frozen === false) {
                return false;
            }
            this._$element.removeClass('frozen');
            this._frozen = false;
            return true;
        },

        /**
         * visible
         * 
         * @access  public
         * @return  Boolean
         */
        visible: function() {
            var visible = this._visible;
            return visible;
        }
    });
});
window.DependencyLoader.push(['BaseModalComponentView'], function() {

    /**
     * BlockModalComponentView
     * 
     * @extends BaseModalComponentView
     */
    window.BlockModalComponentView = BaseModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _keyboardShortcutEscapable
         * 
         * @access  protected
         * @var     Boolean (default: false)
         */
        _keyboardShortcutEscapable: false,

        /**
         * _overlayClickEscapable
         * 
         * @access  protected
         * @var     Boolean (default: false)
         */
        _overlayClickEscapable: false,

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'BlockModalComponentView')
         */
        _string: 'BlockModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        }
    });
});
window.DependencyLoader.push(['BaseModalComponentView'], function() {

    /**
     * BusyModalComponentView
     * 
     * @extends BaseModalComponentView
     */
    window.BusyModalComponentView = BaseModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _keyboardShortcutEscapable
         * 
         * @access  protected
         * @var     Boolean (default: false)
         */
        _keyboardShortcutEscapable: false,

        /**
         * _overlayClickEscapable
         * 
         * @access  protected
         * @var     Boolean (default: false)
         */
        _overlayClickEscapable: false,

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'BusyModalComponentView')
         */
        _string: 'BusyModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * setTheme
         * 
         * @access  public
         * @param   String themeKey
         * @return  Boolean
         */
        setTheme: function(themeKey) {
            this.setAttribute('theme', themeKey);
            return true;
        },

        /**
         * setPrimary
         * 
         * @access  public
         * @param   String msg
         * @return  Boolean
         */
        setPrimary: function(msg) {
            var $primary = this.__find('.primary');
            $primary.innerHTML = msg;
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseModalComponentView'], function() {

    /**
     * ConfirmModalComponentView
     * 
     * @fires   yes
     * @extends BaseModalComponentView
     */
    window.ConfirmModalComponentView = BaseModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _events
         * 
         * @access  protected
         * @var     Function
         */
        _events: function() {
            return Object.assign(this._super(), {

                /**
                 * handleYesFlow
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                handleYesFlow: function(event, $element) {
                    var args = [];
                    this.triggerCustomEvent('yes', args);
                    this.destroy();
                }
            });
        },

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'ConfirmModalComponentView')
         */
        _string: 'ConfirmModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        }
    });
});
window.DependencyLoader.push(['BaseModalComponentView'], function() {

    /**
     * CrashModalComponentView
     * 
     * @extends BaseModalComponentView
     */
    window.CrashModalComponentView = BaseModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _keyboardShortcutEscapable
         * 
         * @access  protected
         * @var     Boolean (default: false)
         */
        _keyboardShortcutEscapable: false,

        /**
         * _killSwitchExemptClickHandlerKeys
         * 
         * @access  protected
         * @var     Array
         */
        _killSwitchExemptClickHandlerKeys: [
            'reload'
        ],

        /**
         * _overlayClickEscapable
         * 
         * @access  protected
         * @var     Boolean (default: false)
         */
        _overlayClickEscapable: false,

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'CrashModalComponentView')
         */
        _string: 'CrashModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * _getCrashDump
         * 
         * @access  protected
         * @return  Object
         */
        _getCrashDump: function() {
            var err = new Error(),
                stack = err.stack,
                dump = {};
            dump.error = {};
            dump.error.stack = stack;
            return dump;
        },

        /**
         * sendCrashReport
         * 
         * @access  public
         * @return  Boolean
         */
        sendCrashReport: function() {
            var data = {},
                dump = this._getCrashDump(),
                options = {};
            options.showCrashModal = false;
            data.dump = JSON.stringify(dump);
            FrameworkUtils.getModel('crash').create(data, options);
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseModalComponentView', 'FormModalComponentView'], function() {

    /**
     * CreateCollectionModalComponentView
     * 
     * @extends FormModalComponentView
     */
    window.CreateCollectionModalComponentView = FormModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'CreateCollectionModalComponentView')
         */
        _string: 'CreateCollectionModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * _handleFormResolvedEvent
         * 
         * @access  protected
         * @param   BaseFormComponentView form
         * @param   Object response
         * @return  Boolean
         */
        _handleFormResolvedEvent: function(form, response) {
            this._super(form, response);
            var user = AuthUtils.getUser(),
                collections = user.getCollections(),
                model = collections.model(),
                publicData = response.data.object,
                collection = model.setActiveRecord(publicData),
                args = [collection];
            collections.add(collection);
            this.triggerCustomEvent('form/resolved', args);
            this.destroy();
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseModalComponentView'], function() {

    /**
     * DownloadModalComponentView
     * 
     * @extends BaseModalComponentView
     */
    window.DownloadModalComponentView = BaseModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _events
         * 
         * @access  protected
         * @var     Function
         */
        _events: function() {
            return Object.assign(this._super(), {

                /**
                 * downloadAndDestroy
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                downloadAndDestroy: function(event, $element) {
                    event.preventDefault();
                    var url = $element.getAttribute('href');
                    WindowUtils.smartDownload(url);
                    this.destroy();
                }
            });
        },

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'DownloadModalComponentView')
         */
        _string: 'DownloadModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        }
    });
});
window.DependencyLoader.push(['BaseModalComponentView', 'FormModalComponentView'], function() {

    /**
     * EditModalComponentView
     * 
     * @extends FormModalComponentView
     */
    window.EditModalComponentView = FormModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'EditModalComponentView')
         */
        _string: 'EditModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this._disableDeleteButton();
            this._setupPopover();
        },

        /**
         * _setupPopover
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupPopover: function() {
            var $popover = this.__find('[data-component-name="EditModalSecondaryPopover"]');
            if ($popover === null) {
                return false;
            }
            var popover = $popover.data.view,
                $reference = this.__components('ContextMenuTrigger')[0];
            popover.setupPopper($reference);
            this._popover = popover;
            return true;
        },

        /**
         * _disableDeleteButton
         * 
         * @access  protected
         * @return  void
         */
        _disableDeleteButton: function() {
            var $delete = this.__lookup('delete');
            if ($delete === null) {
                return false;
            }
            var deletable = this._data.activeRecord.deletable();
            if (deletable === false) {
                $delete.disable();
                return false;
            }
            return true;
        },

        /**
         * _editCollectionModal
         * 
         * @note    @onassar
         * @access  protected
         * @return  Boolean
         */
        _editCollectionModal: function() {
            var activeRecord = this._data.activeRecord,
                type = activeRecord.getActiveRecordType();
            if (type === 'Collection') {
                return true;
            }
            return false;
        },

        /**
         * _showSuccessModal
         * 
         * @access  protected
         * @return  Boolean
         */
        _showSuccessModal: function() {
            if (this._editCollectionModal() === true) {
                this.destroy();
            }
            var primary = 'Changes saved',
                secondary = 'You can continue using Iconduck.';
            ModalUtils.showSuccess(primary, secondary);
            return true;
        },

        /**
         * _handleFormResolvedEvent
         * 
         * @access  protected
         * @param   BaseFormComponentView form
         * @param   Object response
         * @return  Boolean
         */
        _handleFormResolvedEvent: function(form, response) {
            this._super(form, response);
            this._updateActiveRecord(response);
            this._showSuccessModal();
            return false;
        },

        /**
         * _updateActiveRecord
         * 
         * @access  protected
         * @param   Object response
         * @return  Boolean
         */
        _updateActiveRecord: function(response) {
            var publicData = response.data.object;
            this._data.activeRecord.merge(publicData);
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseModalComponentView'], function() {

    /**
     * ErrorModalComponentView
     * 
     * @extends BaseModalComponentView
     */
    window.ErrorModalComponentView = BaseModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'ErrorModalComponentView')
         */
        _string: 'ErrorModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        }
    });
});
window.DependencyLoader.push(['BaseModalComponentView'], function() {

    /**
     * FormModalComponentView
     * 
     * @extends BaseModalComponentView
     */
    window.FormModalComponentView = BaseModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _events
         * 
         * @access  protected
         * @var     Function
         */
        _events: function() {
            return Object.assign(this._super(), {

                /**
                 * submit
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                submit: function(event, $element) {
                    var form = this._getForm();
                    form.submit();
                }
            });
        },

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'FormModalComponentView')
         */
        _string: 'FormModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this._setupForm();
        },

        /**
         * _enableForm
         * 
         * @access  protected
         * @return  Boolean
         */
        _enableForm: function() {
            var form = this._getForm(),
                delay = ConfigUtils.getPublicValue('uiux', 'formModalDelay');
            DataUtils.delay(delay).then(function() {
                form.enable();
            })
            return true;
        },

        /**
         * _getForm
         * 
         * @access  protected
         * @return  BaseFormComponentView
         */
        _getForm: function() {
            var $form = this.__find('form'),
                form = $form.getView();
            return form;
        },

        /**
         * _handleFormReadyEvent
         * 
         * @access  protected
         * @param   BaseFormComponentView form
         * @return  Boolean
         */
        _handleFormReadyEvent: function(form) {
            return true;
        },

        /**
         * _handleFormResolvedEvent
         * 
         * @access  protected
         * @param   BaseFormComponentView form
         * @param   Object response
         * @return  Boolean
         */
        _handleFormResolvedEvent: function(form, response) {
            this._enableForm();
            return true;
        },

        /**
         * _handleFormStateChangeEvent
         * 
         * @access  protected
         * @param   String formStateKey
         * @return  Boolean
         */
        _handleFormStateChangeEvent: function(formStateKey) {
            this._setFormState(formStateKey);
            return true;
        },

        /**
         * _setupForm
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupForm: function() {
            var form = this._getForm(),
                readyHandler = this._handleFormReadyEvent.bind(this),
                resolvedHandler = this._handleFormResolvedEvent.bind(this),
                formStateChangeHandler = this._handleFormStateChangeEvent.bind(this);
            form.addCustomEventListener('ready', readyHandler);
            form.addCustomEventListener('resolved', resolvedHandler);
            form.addCustomEventListener('formState/change', formStateChangeHandler);
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseModalComponentView'], function() {

    /**
     * MailingListModalComponentView
     * 
     * @extends BaseModalComponentView
     */
    window.MailingListModalComponentView = BaseModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'MailingListModalComponentView')
         */
        _string: 'MailingListModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this._setupForm();
        },

        /**
         * _handleFormXHRResolveEvent
         * 
         * @access  protected
         * @param   Object response
         * @return  Boolean
         */
        _handleFormXHRResolveEvent: function(response) {
            this._setUserCookie(response);
            this.destroy();
            this._showSuccessModal();
            ModalUtils.unfreezeVisible();
            return true;
        },

        /**
         * _setupForm
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupForm: function() {
            var $form = this.__find('form'),
                form = $form.getView(),// this.__view($form),//, 'baseFormComponentView'),
                handler = this._handleFormXHRResolveEvent.bind(this);
            this._form = form;
            this._form.setXHRResolveEventHandler(handler);
            return true;
        },

        /**
         * _setUserCookie
         * 
         * @access  protected
         * @param   Object response
         * @return  Boolean
         */
        _setUserCookie: function(response) {
            var key = 'userPublicId',
                value = response.data.object.publicId;
            CookieUtils.set(key, value);
            return true;
        },

        /**
         * _showSuccessModal
         * 
         * @access  protected
         * @return  Boolean
         */
        _showSuccessModal: function() {
            var primary = 'You\'re all set!',
                secondary = 'We\'ll send you a short email when we have new icons and illustrations for you to check out.';
            ModalUtils.showSuccess(primary, secondary);
            return true;
        },

        /**
         * show
         * 
         * @access  public
         * @return  Boolean
         */
        show: function() {
            var response = this._super();
            if (response === false) {
                return false;
            }
            this.autoFocus();
            CookieUtils.set('mailingListModalShown', true);
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseModalComponentView'], function() {

    /**
     * OpenWithFigmaModalComponentView
     * 
     * @extends BaseModalComponentView
     */
    window.OpenWithFigmaModalComponentView = BaseModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _keyboardShortcutEscapable
         * 
         * @access  protected
         * @var     Boolean (default: false)
         */
        // _keyboardShortcutEscapable: false,

        /**
         * _overlayClickEscapable
         * 
         * @access  protected
         * @var     Boolean (default: true)
         */
        // _overlayClickEscapable: true,

        /**
         * _events
         * 
         * @access  protected
         * @var     Function
         */
        _events: function() {
            return Object.assign(this._super(), {

                /**
                 * openWithFigma
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                openWithFigma: function(event, $element) {
                    this._openWithFigma();
                    this.destroy();
                }
            });
        },

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'OpenWithFigmaModalComponentView')
         */
        _string: 'OpenWithFigmaModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * _openWithFigma
         * 
         * @access  protected
         * @return  Boolean
         */
        _openWithFigma: function() {

            // Fingerprinting
            var data = {},
                vector = this._data.vector;
            data.vector = vector.get('publicId');
            data.origin = 'openWithFigma';
            FrameworkUtils.getModel('fingerprint').create(data);

            // Notification
            // var msg = 'Fingerprint created!';
            // NotificationUtils.showDismissGrowl(msg);

            // Open Figma new file
            var url = 'https://www.figma.com/file/new?try-plugin-id=1074084347757622122&try-plugin-version-id=74947&try-plugin-name=Iconduck+-+Icons%2C+emojis%2C+illustrations+and+logos&is-widget=0&is-playground-file=0&mode=design&fuid=972905597725642515&try-plugin-editor-type=design_and_whiteboard';
            window.open(url);
            return true;
        },

        /**
         * show
         * 
         * @access  public
         * @return  Boolean
         */
        show: function() {
            var response = this._super();
            return response;
        }
    });
});
window.DependencyLoader.push(['BaseModalComponentView'], function() {

    /**
     * PreviewModalComponentView
     * 
     * @extends BaseModalComponentView
     */
    window.PreviewModalComponentView = BaseModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _$downloadPopover
         * 
         * @access  protected
         * @var     null|HTMLElement (default: null)
         */
        _$downloadPopover: null,

        /**
         * _downloadPopover
         * 
         * @access  protected
         * @var     null|DownloadPopoverComponentView (default: null)
         */
        _downloadPopover: null,

        /**
         * _drift
         * 
         * @access  protected
         * @var     null|Drift (default: null)
         */
        _drift: null,

        /**
         * _handlers
         * 
         * Stores references to handlers that may be need later on (for example
         * to remove specific event handlers after this modal is closed).
         * 
         * @access  protected
         * @var     Boolean (default: {})
         */
        _handlers: {},

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'PreviewModalComponentView')
         */
        _string: 'PreviewModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this._addElementHideStackUtilsRunEventListener();
            this._addImageContextMenuEventListener();
            this._drawDownloadPopover();
            this._setupDownloadPopover();
            this._setupThumbZoom();
            this._addDownloadClickEventListener();
            this._addNavigationEventListeners();
        },

        /**
         * _addImageContextMenuEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addImageContextMenuEventListener: function() {
            var $img = this.__find('img');
            $img.addEventListener('contextmenu', function(event) {
                event.preventDefault();
            });
            return true;
        },

        /**
         * _addDownloadClickEventListener
         * 
         * @access  protected
         * @return  void
         */
        _addDownloadClickEventListener: function() {
            var $button = this._getDownloadButtonElement(),
                handler = this._handleDownloadClickEvent.bind(this);
            $button.addEventListener('click', function(event) {
                event.preventDefault();
                handler();
            });
        },

        /**
         * _addElementHideStackUtilsRunEventListener
         * 
         * @access  protected
         * @return  void
         */
        _addElementHideStackUtilsRunEventListener: function() {
            this.addCustomEventListener('elementHideStackUtils/run', function() {
                StateUtils.pushInitialState();
            });
        },

        /**
         * _addNavigationEventListeners
         * 
         * @access  protected
         * @return  void
         */
        _addNavigationEventListeners: function() {
            this._addNextClickEventListener();
            this._addNextKeyDownEventListener();
            this._addPreviousClickEventListener();
            this._addPreviousKeyDownEventListener();
        },

        /**
         * _addNextClickEventListener
         * 
         * @access  protected
         * @return  void
         */
        _addNextClickEventListener: function() {
            var $element = this.__lookup('next'),
                handler = this._handleNextClickEvent.bind(this);
            $element.addEventListener('click', function(event) {
                event.preventDefault();
                handler();
            });
        },

        /**
         * _addNextKeyDownEventListener
         * 
         * @access  protected
         * @return  void
         */
        _addNextKeyDownEventListener: function() {
            var handler = this._handlers.nextKeyDownEventHandler = this._handleNextKeyDownEvent.bind(this);
            window.addEventListener('keydown', handler);
        },

        /**
         * _addPreviousClickEventListener
         * 
         * @access  protected
         * @return  void
         */
        _addPreviousClickEventListener: function() {
            var $element = this.__lookup('previous'),
                handler = this._handlePreviousClickEvent.bind(this);
            $element.addEventListener('click', function(event) {
                event.preventDefault();
                handler();
            });
        },

        /**
         * _addPreviousKeyDownEventListener
         * 
         * @access  protected
         * @return  void
         */
        _addPreviousKeyDownEventListener: function() {
            var handler = this._handlers.previousKeyDownEventHandler = this._handlePreviousKeyDownEvent.bind(this);
            window.addEventListener('keydown', handler);
        },

        /**
         * _drawDownloadPopover
         * 
         * @access  protected
         * @return  Boolean
         */
        _drawDownloadPopover: function() {
            var templateName = 'DownloadPopoverComponent',
                data = this._getDownloadPopoverData(),
                $downloadPopover = ElementUtils.renderTemplate(templateName, data),
                $parent = this._$element;
            $parent.append($downloadPopover);
            this._$downloadPopover = $downloadPopover;
            return true;
        },

        /**
         * _getDownloadButtonElement
         * 
         * @access  protected
         * @return  HTMLButtonElement
         */
        _getDownloadButtonElement: function() {
            var $button = this.__find('.button.primary');
            return $button;
        },

        /**
         * _getDownloadPopover
         * 
         * @access  protected
         * @return  null|DownloadPopoverComponentView
         */
        _getDownloadPopover: function() {
            var downloadPopover = this.getComponent('downloadPopover');
            return downloadPopover;
        },

        /**
         * _getDownloadPopoverData
         * 
         * @access  protected
         * @return  Object
         */
        _getDownloadPopoverData: function() {
            var data = {};
            data.vector = this._data.vector;
            return data;
        },

        /**
         * _getNextVector
         * 
         * @access  protected
         * @return  Promise
         */
        _getNextVector: function() {
            var current = this._data.vector,
                promise = this._data.vectorsCollection.next(current);
            return promise;
        },

        /**
         * _getPreviousVector
         * 
         * @access  protected
         * @return  Promise
         */
        _getPreviousVector: function() {
            var current = this._data.vector,
                promise = this._data.vectorsCollection.previous(current);
            return promise;
        },

        /**
         * _handleDownloadClickEvent
         * 
         * @access  protected
         * @return  void
         */
        _handleDownloadClickEvent: function() {
            // var alternate = this._imageError === true;
            this._data.vector.download('svg');
        },

        /**
         * _handleNextClickEvent
         * 
         * @access  protected
         * @return  Boolean
         */
        _handleNextClickEvent: function() {
            var response = this._showNext();
            return response;
        },

        /**
         * _handleNextKeyDownEvent
         * 
         * @access  protected
         * @param   Object event
         * @return  Boolean
         */
        _handleNextKeyDownEvent: function(event) {
            if (event.metaKey === true) {
                return false;
            }
            var last = ModalUtils.getLastVisible();
            if (last !== this) {
                return false;
            }
            // if (event.metaKey === true) {
                // console.log('metaKey', event);
                // return false;
            // }
            if (event.shiftKey === true) {
                // console.log('shiftKey', event);
                return false;
            }
            var code = event.code || '';
            code = code.toLowerCase();
            if (code === 'arrowright') {
                var response = this._showNext();
                return response;
            }
            return false;
        },

        /**
         * _handlePreviousClickEvent
         * 
         * @access  protected
         * @return  Boolean
         */
        _handlePreviousClickEvent: function() {
            var response = this._showPrevious();
            return response;
        },

        /**
         * _handlePreviousKeyDownEvent
         * 
         * @access  protected
         * @param   Object event
         * @return  Boolean
         */
        _handlePreviousKeyDownEvent: function(event) {
            if (event.metaKey === true) {
                return false;
            }
            var last = ModalUtils.getLastVisible();
            if (last !== this) {
                return false;
            }
            if (event.shiftKey === true) {
                return false;
            }
            var code = event.code || '';
            code = code.toLowerCase();
            if (code === 'arrowleft') {
                var response = this._showPrevious();
                return response;
            }
            return false;
        },

        /**
         * _preloadNextSibling
         * 
         * @access  protected
         * @return  Promise
         */
        _preloadNextSibling: function() {
            var promise = this._getNextVector().then(function(sibling) {
                if (sibling === null) {
                    return false;
                }
                return sibling.preload();
            });
            return promise;
        },

        /**
         * _preloadPreviousSibling
         * 
         * @access  protected
         * @return  Promise
         */
        _preloadPreviousSibling: function() {
            var promise = this._getPreviousVector().then(function(sibling) {
                if (sibling === null) {
                    return false;
                }
                return sibling.preload();
            });
            return promise;
        },

        /**
         * _preloadSiblings
         * 
         * @access  protected
         * @return  void
         */
        _preloadSiblings: function() {
            var handler = this._preloadPreviousSibling.bind(this);
            this._preloadNextSibling().then(handler);
        },

        /**
         * _removeNextKeyDownEventListener
         * 
         * @access  protected
         * @return  void
         */
        _removeNextKeyDownEventListener: function() {
            var handler = this._handlers.nextKeyDownEventHandler;
            window.removeEventListener('keydown', handler);
        },

        /**
         * _removePreviousKeyDownEventListener
         * 
         * @access  protected
         * @return  void
         */
        _removePreviousKeyDownEventListener: function() {
            var handler = this._handlers.previousKeyDownEventHandler;
            window.removeEventListener('keydown', handler);
        },

        /**
         * _setClasses
         * 
         * @access  protected
         * @return  Boolean
         */
        _setClasses: function() {
            var $element = this._$element,
                classes = this._data.vector.getStylePropertyClasses();
            classes.push('modal');
            this._$element.className = classes.join(' ');
            return true;
        },

        /**
         * _setupDownloadPopover
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupDownloadPopover: function() {
            var $downloadPopover = this._$downloadPopover,
                downloadPopover = $downloadPopover.data.view,
                $reference = this.__lookup('vectorSecondary');
            downloadPopover.setupPopper($reference);
            this._downloadPopover = downloadPopover;
            return true;
        },

        /**
         * _setupThumbZoom
         * 
         * @see     https://github.com/imgix/drift#basic-usage
         * @access  protected
         * @return  Boolean
         */
        _setupThumbZoom: function() {
            // var admin = AuthUtils.admin();
            // if (admin === false) {
            //     return false;
            // }
            var url = this._data.vector.getPNGURL(1024);
            RequestUtils.loadImage(url);
            var $img = this.__find('img'),
                $pane = this.__find('section'),
                drift = new Drift($img, {
                    handleTouch: false,
                    containInline: true,
                    paneContainer: $pane,
                    hoverBoundingBox: true,
                    showWhitespaceAtEdges: true
                });
            this._drift = drift;
            return true;
        },

        /**
         * _showDownloadPopover
         * 
         * @access  protected
         * @return  Boolean
         */
        _showDownloadPopover: function() {
            this._downloadPopover.show();
            return true;
        },

        /**
         * _showNext
         * 
         * @todo    Ensure vector is visible in viewport
         * @todo    Trigger focus CSS for selected vector
         * @access  protected
         * @return  Boolean
         */
        _showNext: function() {
            if (this._validShowNextAttempt() === false) {
                return false;
            }
            ModalUtils.showBusy();
            var promise = this._getNextVector(),
                collection = this._data.vectorsCollection,
                currentPreviewModal = this;
            promise.then(function(next) {
                return next.preload();
            }).then(function(next) {
                next.trackPushState(next.getPath());
                ModalUtils.hideBusy();
                currentPreviewModal.destroy();
                ModalUtils.showPreview(next, collection);
                return true;
            });
            return true;
        },

        /**
         * _showPrevious
         * 
         * @access  protected
         * @return  Boolean
         */
        _showPrevious: function() {
            if (this._validShowPreviousAttempt() === false) {
                return false;
            }
            ModalUtils.showBusy();
            var promise = this._getPreviousVector(),
                collection = this._data.vectorsCollection,
                currentPreviewModal = this;
            promise.then(function(previous) {
                return previous.preload();
            }).then(function(previous) {
                previous.trackPushState(previous.getPath());
                ModalUtils.hideBusy();
                currentPreviewModal.destroy();
                ModalUtils.showPreview(previous, collection);
                return true;
            });
            return true;
        },

        /**
         * _validShowNextAttempt
         * 
         * @access  protected
         * @return  Boolean
         */
        _validShowNextAttempt: function() {
            if (this._visible === false) {
                return false;
            }
            var busy = ModalUtils.getBusy();
            if (busy !== null) {
                return false;
            }
            var loader = this._data.vectorsCollection.getLoader();
            if (loader !== null) {
                if (loader.loading() === true) {
                    return false;
                }
            }
            if (this._data.vector === this._data.vectorsCollection.last()) {
                if (loader === null) {
                    return false;
                }
                if (this._data.vectorsCollection.more() === true) {
                    return true;
                }
                return false;
            }
            return true;
        },

        /**
         * _validShowPreviousAttempt
         * 
         * @access  protected
         * @return  Boolean
         */
        _validShowPreviousAttempt: function() {
            if (this._visible === false) {
                return false;
            }
            var busy = ModalUtils.getBusy();
            if (busy !== null) {
                return false;
            }
            if (this._data.vector === this._data.vectorsCollection.first()) {
                return false;
            }
            return true;
        },

        /**
         * hide
         * 
         * @access  public
         * @param   undefined|Object options (default: {})
         * @return  Boolean
         */
        hide: function(options) {
            options = options || {};
            var response = this._super(options);
            if (response === false) {
                return false;
            }
            __Iconduck.page.clearVectorBlockPreviewStates();
            this._removeNextKeyDownEventListener();
            this._removePreviousKeyDownEventListener();
            this._getDownloadPopover().hide();
            return true;
        },

        /**
         * show
         * 
         * @access  public
         * @return  Boolean
         */
        show: function() {
            var response = this._super();
            if (response === false) {
                return false;
            }
            this._data.vector.triggerCustomEvent('preview');
            this._preloadSiblings();
            this._setClasses();
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseModalComponentView'], function() {

    /**
     * PromotionModalComponentView
     * 
     * @todo    Create Bitly short links (secondary tracking)
     * @todo    Track userIds (?)
     * 
     * @todo    [DONE] Markup
     * @todo    [DONE] Determine logic for auto showing (every 4 images)
     * @todo    [DONE] - Ensure this doesn't conflict with autoShowMailingListModal
     * @todo    [DONE] Look into better cache flows for configs (buggy...)
     * @todo    [DONE] - For example, what if template file isn't available.. again..
     * @todo    [DONE] - e.g. the way Licenses wasn't
     * @todo    [DONE] - https://dash.cloudflare.com/c1eef8aac52fb8efe0cb43da8ea112c3/iconduck.com/rules
     * @todo    [DONE] - https://dev.iconduck.com/utils/config/public?v=2023-08-07.00
     * @extends BaseModalComponentView
     */
    window.PromotionModalComponentView = BaseModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _keyboardShortcutEscapable
         * 
         * @access  protected
         * @var     Boolean (default: false)
         */
        _keyboardShortcutEscapable: false,

        /**
         * _overlayClickEscapable
         * 
         * @access  protected
         * @var     Boolean (default: false)
         */
        // _overlayClickEscapable: false,

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'PromotionModalComponentView')
         */
        _string: 'PromotionModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * show
         * 
         * @access  public
         * @return  Boolean
         */
        show: function() {
            var response = this._super();
            if (response === false) {
                return false;
            }
            CookieUtils.set('promotionModalShown', true);
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseModalComponentView'], function() {

    /**
     * SettingsModalComponentView
     * 
     * @extends BaseModalComponentView
     */
    window.SettingsModalComponentView = BaseModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _events
         * 
         * @access  protected
         * @var     Function
         */
        _events: function() {
            return Object.assign(this._super(), {

                /**
                 * showUpdateEmailAddressState
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                showUpdateEmailAddressState: function(event, $element) {
                    this._setState('updateEmailAddress');
                },

                /**
                 * showUpdateNotificationsState
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                showUpdateNotificationsState: function(event, $element) {
                    this._setState('updateNotifications');
                },

                /**
                 * showUpdatePasswordState
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                showUpdatePasswordState: function(event, $element) {
                    this._setState('updatePassword');
                }
            });
        },

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'SettingsModalComponentView')
         */
        _string: 'SettingsModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this._addStateChangeEventListener();
            this._setState('updateEmailAddress');
        },

        /**
         * _addStateChangeEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addStateChangeEventListener: function() {
            var handler = this._handleStateChangeEvent.bind(this);
            this.addCustomEventListener('state/change', handler)
            return true;
        },

        /**
         * _handleStateChangeEvent
         * 
         * @access  protected
         * @param   String stateKey
         * @return  Boolean
         */
        _handleStateChangeEvent: function(stateKey) {
            var $links = this.__find('div.links div.link a', true);
            $links.removeClass('active');
            var $active = this.__lookup(stateKey);
            $active.addClass('active');
            var state = this._getState(stateKey);
            state.autoFocus();
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseModalComponentView'], function() {

    /**
     * SpotlightModalComponentView
     * 
     * @todo    When escape is pressed with value, clear input before hiding
     * @todo    On prod, race condition between command+k plus user lookup
     * 
     * @todo    Mark current page
     * @todo    - Prevent re-load
     * @todo    Add individual collection pages
     * @todo    Add vector set counts
     * 
     * @todo    [DONE] Bug when spotlight not available yet
     * @todo    [ISH ] Escape key via input should hide
     * @todo    [DONE] Max-height
     * @todo    [DONE] Input change event
     * @todo    [DONE] Bug with pathing: https://s3.us-west-2.amazonaws.com/onassar.prod.03/apps/secure-shots/v0.0.1/qqh9dq92nh/Screenshot%202023-08-07%20at%207.43.58%20AM.jpg
     * @todo    [DONE] Style: https://s3.us-west-2.amazonaws.com/onassar.prod.03/apps/secure-shots/v0.0.1/qqh9dq92nh/Screenshot%202023-08-07%20at%207.37.38%20AM.jpg
     * @todo    [DONE] State switching
     * @todo    [DONE] Search result display
     * @todo    [DONE] Empty state
     * @todo    [NOPE] Highlight matching query
     * @todo    [DONE] Tab/shift-tab keys
     * @todo    [NOPE] - Tabindex work
     * @todo    [DONE] Up/down keys
     * @todo    [ISH ] Enter key
     *          [ISH ] - Buggy with shift/command keys
     * @todo    [DONE] Pass down map of vector sets (limited to admins rn)
     * @todo    [DONE] Navigation events
     * 
     * @see     https://sizzy.co/
     * @see     https://s3.us-west-2.amazonaws.com/onassar.prod.03/apps/secure-shots/v0.0.1/qqh9dq92nh/Screenshot%202023-08-07%20at%201.37.10%20AM.jpg
     * @extends BaseModalComponentView
     */
    window.SpotlightModalComponentView = BaseModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _focused
         * 
         * @access  protected
         * @var     Number (default: -1)
         */
        _focused: -1,

        /**
         * _results
         * 
         * @access  protected
         * @var     Object (default: {})
         */
        _results: {},

        /**
         * _stateKey
         * 
         * @access  protected
         * @var     String (default: 'default')
         */
        _stateKey: 'default',

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'SpotlightModalComponentView')
         */
        _string: 'SpotlightModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this._renderDefaultState();
            this._renderIndexState();
            this._addNavigationEventListeners();
            this._addSearchInputEventListener();
            this._addResultClickEventListeners();
        },

        /**
         * _addNavigationEventListeners
         * 
         * @access  protected
         * @return  Boolean
         */
        _addNavigationEventListeners: function() {
            var handler = this._handleNavigationEvent.bind(this);
            window.addEventListener('keydown', handler);
            return true;
        },

        /**
         * _addResultClickEventListeners
         * 
         * @access  protected
         * @return  Boolean
         */
        _addResultClickEventListeners: function() {
            var all = true,
                $results = this.__find('.result', all),
                handler = this._handleResultClickEvent.bind(this);
            $results.addEventListener('click', handler);
            return true;
        },

        /**
         * _addSearchInputEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addSearchInputEventListener: function() {
            var $search = this.__find('input'),
                handler = this._handleSearchInputEvent.bind(this);
            $search.addEventListener('input', handler);
            return true;
        },

        /**
         * _getFocused
         * 
         * @access  protected
         * @return  null|Object
         */
        _getFocused: function() {
            var $focused = this.__find('.state.default:not(.display-none) .result.focused');
            if ($focused !== null) {
                var obj = {};
                obj.destination = $focused.closest('.result').getAttribute('data-destination');
                return obj;
            }
            $focused = this.__find('.state.index:not(.display-none) .result.focused');
            if ($focused !== null) {
                var obj = {};
                obj.destination = $focused.closest('.result').getAttribute('data-destination');
                return obj;
            }
            return null;
        },

        /**
         * _handleNavigationEvent
         * 
         * @access  protected
         * @param   Object event
         * @return  Boolean
         */
        _handleNavigationEvent: function(event) {
            if (this.visible() === false) {
                return false;
            }
            var code = event.code || '';
            code = code.toLowerCase();
            if (code === 'arrowdown') {
                event.preventDefault();
                this.next();
                return true;
            }
            if (code === 'arrowup') {
                event.preventDefault();
                this._previous();
                return true;
            }
            if (code === 'enter' && event.metaKey === false) {
                var focused = this._getFocused();
                if (focused === null) {
                    return false;
                }
                var destination = focused.destination;
                this._openResult(destination, false);
                return true;
            }
            if (code === 'enter' && event.metaKey === true) {
                var focused = this._getFocused();
                if (focused === null) {
                    return false;
                }
                var destination = focused.destination;
                this._openResult(destination, true);
                return true;
            }
            if (code === 'tab' && event.shiftKey === false) {
                event.preventDefault();
                this.next();
                return true;
            }
            if (code === 'tab' && event.shiftKey === true) {
                event.preventDefault();
                this._previous();
                return true;
            }
            return false;
        },

        /**
         * _handleResultClickEvent
         * 
         * @access  protected
         * @param   Object event
         * @return  Boolean
         */
        _handleResultClickEvent: function(event) {
            var $target = event.target,
                $result = $target.closest('.result'),
                destination = $result.getAttribute('data-destination');
            this._openResult(destination, false);
            return true;
        },

        /**
         * _handleSearchInputEvent
         * 
         * @access  protected
         * @param   Object event
         * @return  Boolean
         */
        _handleSearchInputEvent: function(event) {
            var $search = this.__find('input'),
                value = $search.value.trim();
            if (value === '') {
                this.setState('default');
                this.next();
                return true;
            }
            var results = this._searchResults(value);
            if (results.length === 0) {
                this.setState('empty');
                return true;
            }
            this.__find('.state.index .result', true).addClass('display-none');
            for (var result of results) {
                var path = result.destination,
                    selector = '.state.index [data-destination="' + (path) + '"]',
                    $row = this.__find(selector);
                $row.removeClass('display-none');
            }
            this.setState('index');
            this.next();
// console.log(
//     this.__find('.state.index .result:not(.display-none)')
// );
            // this.__find('.state.index .result:not(.display-none)').focus();
            this.__find('.state.index .result.focused', true).removeClass('focused');
            this.__find('.state.index .result:not(.display-none)').addClass('focused');
            return true;
        },

        /**
         * _openResult
         * 
         * @access  protected
         * @param   String destination
         * @param   Boolean newTab
         * @return  Boolean
         */
        _openResult: function(destination, newTab) {
            if (destination.match(/^http/i) !== null) {
                window.open(destination);
                return true;
            }
            if (newTab === true) {
                window.open(destination);
                return true;
            }
            ModalUtils.showBusy('Loading...');
            window.location.href = destination;
            return true;
        },

        /**
         * _previous
         * 
         * @access  protected
         * @return  Boolean
         */
        _previous: function() {
            if (this._stateKey === 'empty') {
                return false;
            }
            if (this._focused === 0) {
                return false;
            }
            this._focused--;
            var stateKey = this._stateKey,
                $state = this.__find('.state.' + (stateKey));
            this.__find('.state.' + (stateKey) + ' .result.focused', true).removeClass('focused');
            var $results = this.__find('.state.' + (stateKey) + ' .result:not(.display-none)', true);
            $results[this._focused].addClass('focused');
            return true;
        },

        /**
         * _renderDefaultState
         * 
         * @access  public
         * @return  Boolean
         */
        _renderDefaultState: function() {
            var results = SpotlightUtils.getDefaultStateResults(),
                $default = this.__find('.states .state.default'),
                $results = $default.querySelector('.results'),
                templateName = 'SpotlightResultRowBlockComponent';
            this._results.default = results;
            for (var result of results) {
                var data = result,
                    $row = ElementUtils.renderTemplate(templateName, data);
                $results.appendChild($row);
            }
            return true;
        },

        /**
         * _renderIndexState
         * 
         * @access  public
         * @return  Boolean
         */
        _renderIndexState: function() {
            var results = SpotlightUtils.getIndexStateResults(),
                $index = this.__find('.states .state.index'),
                $results = $index.querySelector('.results'),
                templateName = 'SpotlightResultRowBlockComponent';
            this._results.index = results;
            for (var result of results) {
                var data = result,
                    $row = ElementUtils.renderTemplate(templateName, data);
                $results.appendChild($row);
            }
            return true;
        },

        /**
         * _searchResults
         * 
         * @access  protected
         * @param   String query
         * @return  Array
         */
        _searchResults: function(query) {
            var indexResults = [];
            for (var result of this._results.index) {
                var regExp = new RegExp(query, 'i');
                if (result.label.match(regExp) === null) {
                    continue;
                }
                indexResults.push(result);
            }
            return indexResults;
        },

        /**
         * destroy
         * 
         * @access  public
         * @param   undefined|Object options (default: {})
         * @return  Boolean
         */
        destroy: function(options) {
            options = options || {};
            this.triggerCustomEvent('destroy');
            // this._super();
            this.hide(options);
            return true;
        },

        /**
         * next
         * 
         * @access  public
         * @return  Boolean
         */
        next: function() {
            if (this._stateKey === 'empty') {
                return false;
            }
            var stateKey = this._stateKey,
                $results = this.__find('.state.' + (stateKey) + ' .result:not(.display-none)', true);
            if (this._focused === $results.length - 1) {
                return false;
            }
            this._focused++;
            this.__find('.state.' + (stateKey) + ' .result.focused', true).removeClass('focused');
            $results[this._focused].addClass('focused');
            return true;
        },

        /**
         * resetSearchInput
         * 
         * @access  public
         * @return  Boolean
         */
        resetSearchInput: function() {
            var $search = this.__find('input');
            $search.value = '';
            return true;
        },

        /**
         * setState
         * 
         * @access  public
         * @param   String stateKey
         * @return  Boolean
         */
        setState: function(stateKey) {
            this._stateKey = stateKey;
            this._focused = -1;
            var all = true,
                $states = this.__find('.states .state', all);
            $states.addClass('display-none');
            var selector = '.state.' + (stateKey),
                $state = this.__find(selector);
            $state.removeClass('display-none');
            return true;
        },

        /**
         * show
         * 
         * @access  public
         * @return  Boolean
         */
        show: function() {
            var response = this._super();
            if (response === false) {
                return false;
            }
            this.setState('default');
            this.next();
            return true;
        },

        /**
         * toggle
         * 
         * @access  public
         * @return  Boolean
         */
        toggle: function() {
            if (this.visible() === true) {
                this.hide();
                return false;
            }
            this.show();
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseModalComponentView'], function() {

    /**
     * SuccessModalComponentView
     * 
     * @extends BaseModalComponentView
     */
    window.SuccessModalComponentView = BaseModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'SuccessModalComponentView')
         */
        _string: 'SuccessModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        }
    });
});
window.DependencyLoader.push(['BaseModalComponentView'], function() {

    /**
     * UpsellModalComponentView
     * 
     * @extends BaseModalComponentView
     */
    window.UpsellModalComponentView = BaseModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'UpsellModalComponentView')
         */
        _string: 'UpsellModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        }
    });
});
window.DependencyLoader.push(['BaseModalComponentView', 'FormModalComponentView'], function() {

    /**
     * VectorDownloadCustomSizeModalComponentView
     * 
     * @extends FormModalComponentView
     */
    window.VectorDownloadCustomSizeModalComponentView = FormModalComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'VectorDownloadCustomSizeModalComponentView')
         */
        _string: 'VectorDownloadCustomSizeModalComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        }
    });
});
window.DependencyLoader.push(['BaseComponentView'], function() {

    /**
     * BaseNotificationComponentView
     * 
     * @extends BaseComponentView
     */
    window.BaseNotificationComponentView = BaseComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'BaseNotificationComponentView')
         */
        _string: 'BaseNotificationComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        }
    });
});
window.DependencyLoader.push(['BaseNotificationComponentView'], function() {

    /**
     * GrowlNotificationComponentView
     * 
     * @todo    Add event that prevents hiding of the growl if mouse over
     * @todo    Add collision detection (eg. growl called while growl is already
     *          showing; only ever show one, but swap out content)
     * @extends BaseNotificationComponentView
     */
    window.GrowlNotificationComponentView = BaseNotificationComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _action
         * 
         * @access  protected
         * @var     nulString (default: 'dismiss')
         */
        _action: 'dismiss',

        /**
         * _actionProperties
         * 
         * @access  protected
         * @var     Objet (default: {})
         */
        _actionProperties: {},

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'GrowlNotificationComponentView')
         */
        _string: 'GrowlNotificationComponentView',

        /**
         * _slideDuration
         * 
         * @access  protected
         * @var     null|Number (default: 325)
         */
        _slideDuration: 325,

        /**
         * _timeout
         * 
         * @access  protected
         * @var     null|Number (default: 3000)
         */
        _timeout: 3000,

        /**
         * _timeoutReference
         * 
         * @access  protected
         * @var     null|Number (default: null)
         */
        _timeoutReference: null,

        /**
         * _visible
         * 
         * @access  protected
         * @var     Boolean (default: false)
         */
        _visible: false,

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this._addDismissClickEventListener();
            this._addHideClickEventListener();
            this._addReloadClickEventListener();
            this._addViewLikesPageClickEventListener();
        },

        /**
         * _addDismissClickEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addDismissClickEventListener: function() {
            var $element = this.__lookup('dismiss'),
                handler = this._handleDismissClickEvent.bind(this);
            $element.addEventListener('click', function(event) {
                event.preventDefault();
                handler();
            });
            return true;
        },

        /**
         * _addHideClickEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addHideClickEventListener: function() {
            var $element = this.__lookup('hide'),
                handler = this._handleHideClickEvent.bind(this);
            $element.addEventListener('click', function(event) {
                event.preventDefault();
                handler();
            });
            return true;
        },

        /**
         * _addReloadClickEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addReloadClickEventListener: function() {
            var $element = this.__lookup('reload'),
                handler = this._handleReloadClickEvent.bind(this);
            $element.addEventListener('click', function(event) {
                event.preventDefault();
                handler();
            });
            return true;
        },

        /**
         * _addViewLikesPageClickEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addViewLikesPageClickEventListener: function() {
            var $element = this.__lookup('viewLikesPage'),
                handler = this._handleViewLikesPageClickEvent.bind(this);
            $element.addEventListener('click', function(event) {
                event.preventDefault();
                handler();
            });
            return true;
        },

        /**
         * _handleDismissClickEvent
         * 
         * @access  protected
         * @return  Boolean
         */
        _handleDismissClickEvent: function() {
            var response = this.hide();
            return true;
        },

        /**
         * _handleHideClickEvent
         * 
         * @access  protected
         * @return  Boolean
         */
        _handleHideClickEvent: function() {
            var response = this.hide();
            return response;
        },

        /**
         * _handleReloadClickEvent
         * 
         * @access  protected
         * @return  Boolean
         */
        _handleReloadClickEvent: function() {
            var properties = this._actionProperties.reload || {},
                destination = properties.destination || null;
            if (destination === null) {
                window.location.reload();
                return true;
            }
            window.location.href = destination;
            return true;
        },

        /**
         * _handleViewLikesPageClickEvent
         * 
         * @access  protected
         * @return  Boolean
         */
        _handleViewLikesPageClickEvent: function() {
            var path = '/likes';
            window.location.href = path;
            return true;
        },

        /**
         * extendTimeout
         * 
         * @access  public
         * @param   Number milliseconds
         * @return  Boolean
         */
        // extendTimeout: function(milliseconds) {
        //     var _this = this;
        //     clearTimeout(this._timeoutReference);
        //     this._timeoutReference = setTimeout(function() {
        //         _this.hide();
        //     }, milliseconds);
        //     return true;
        // },

        /**
         * _destroy
         * 
         * @access  protected
         * @return  Boolean
         */
        _destroy: function() {
            var response = this.destroy();
            return response;
        },

        /**
         * hide
         * 
         * @access  public
         * @return  Boolean
         */
        hide: function() {
            if (this._visible === false) {
                return false;
            }
            clearTimeout(this._timeoutReference);
            this._visible = false;
            var $element = this._$element;
            $element.addClass('invisible');
            $element.removeClass('down');
            $element.addClass('up');
            var slideDuration = this._slideDuration,
                destroy = this._destroy.bind(this);
            setTimeout(function() {
                $element.addClass('display-none');
                destroy();
            }, slideDuration);
            return true;
        },

        /**
         * setAction
         * 
         * @access  public
         * @param   String action
         * @return  Boolean
         */
        setAction: function(action) {
            this._action = action;
            var selector = 'div.actions a',
                $actions = this.__find(selector, true);
            for (var $action of $actions) {
                $action.addClass('display-none');
            }
            if (action === 'dismiss') {
                var $element = this.__lookup('dismiss');
                $element.removeClass('display-none');
            }
            if (action === 'reload') {
                var $element = this.__lookup('reload');
                $element.removeClass('display-none');
            }
            if (action === 'viewLikesPage') {
                var $element = this.__lookup('viewLikesPage');
                $element.removeClass('display-none');
            }
            return false;
        },

        /**
         * setActionProperties
         * 
         * @access  public
         * @param   String action
         * @param   Object properties
         * @return  Boolean
         */
        setActionProperties: function(action, properties) {
            this._actionProperties[action] = properties;
            return true;
        },

        /**
         * setTimeout
         * 
         * @access  public
         * @param   null|Number milliseconds
         * @return  void
         */
        setTimeout: function(milliseconds) {
            this._timeout = milliseconds;
        },

        /**
         * show
         * 
         * @access  public
         * @param   String msg
         * @return  Boolean
         */
        show: function(msg) {
            if (this._visible === true) {
                return false;
            }
            this._visible = true;
            var $element = this._$element;
            $element.removeClass('display-none');
            setTimeout(function() {
                $element.removeClass('invisible');
                $element.removeClass('up');
                $element.addClass('down');
            }, 0);
            var _this = this,
                timeout = this._timeout;
            if (timeout === null) {
                return false;
            }
            var handler = this.hide.bind(this);
            this._timeoutReference = setTimeout(handler, timeout);
            return true;
        },

        /**
         * visible
         * 
         * @access  public
         * @return  Boolean
         */
        visible: function() {
            var visible = this._visible;
            return visible;
        }
    });
});
window.DependencyLoader.push(['BasePopoverComponentView'], function() {

    /**
     * AccountPopoverComponentView
     * 
     * @extends BasePopoverComponentView
     */
    window.AccountPopoverComponentView = BasePopoverComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _popperOffset
         * 
         * @access  protected
         * @var     String (default: [0, 6])
         */
        _popperOffset: [-62, 10],

        /**
         * _popperPlacement
         * 
         * @access  protected
         * @var     String (default: 'bottom')
         */
        _popperPlacement: 'bottom',

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'AccountPopoverComponentView')
         */
        _string: 'AccountPopoverComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * destroy
         * 
         * @throws  Error
         * @access  public
         * @return  Booelan
         */
        destroy: function() {
            var msg = 'Cannot be destroyed';
            throw new Error(msg);
            return false;
        }
    });
});
window.DependencyLoader.push(['BaseComponentView'], function() {

    /**
     * BasePopoverComponentView
     * 
     * @extends BaseComponentView
     */
    window.BasePopoverComponentView = BaseComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _popper
         * 
         * @link    https://popper.js.org/
         * @access  protected
         * @var     null|Popper (default: null)
         */
        _popper: null,

        /**
         * _popperOffset
         * 
         * @access  protected
         * @var     String (default: [0, 0])
         */
        _popperOffset: [0, 0],

        /**
         * _popperPlacement
         * 
         * @access  protected
         * @var     String (default: 'right')
         */
        _popperPlacement: 'right',

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'BasePopoverComponentView')
         */
        _string: 'BasePopoverComponentView',

        /**
         * _visible
         * 
         * @access  protected
         * @var     Boolean (default: false)
         */
        _visible: false,

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * destroy
         * 
         * @access  public
         * @return  Boolean
         */
        destroy: function() {
            this._super();
            this.hide();
            return true;
        },

        /**
         * hide
         * 
         * @access  public
         * @return  Boolean
         */
        hide: function() {
            if (this._visible === false) {
                return false;
            }
            ElementHideStackUtils.remove(this);
            this._visible = false;
            this._addHiddenClass();
            return true;
        },

        /**
         * setupPopper
         * 
         * @see     https://popper.js.org/docs/v2/
         * @see     https://popper.js.org/docs/v2/modifiers/
         * @see     https://popper.js.org/docs/v2/modifiers/popper-offsets/
         * @access  public
         * @param   HTMLElement $reference
         * @return  void
         */
        setupPopper: function($reference) {
            var $element = this._$element,
                popper = Popper.createPopper($reference, $element, {
                    placement: this._popperPlacement,
                    modifiers: [{
                        name: 'offset',
                        options: {
                            offset: this._popperOffset
                        }
                    }] 
                });
            this._popper = popper;
        },

        /**
         * show
         * 
         * @access  public
         * @return  Boolean
         */
        show: function() {
            if (this._visible === true) {
                return false;
            }
            ElementHideStackUtils.push(this, this.hide);
            this._visible = true;
            this._removeHiddenClass();
            this._popper.forceUpdate();
            return true;
        },

        /**
         * visible
         * 
         * @access  public
         * @return  Boolean
         */
        visible: function() {
            var visible = this._visible;
            return visible;
        }
    });
});
window.DependencyLoader.push(['BasePopoverComponentView'], function() {

    /**
     * CollectionContextMenuPopoverComponentView
     * 
     * @extends BasePopoverComponentView
     */
    window.CollectionContextMenuPopoverComponentView = BasePopoverComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _events
         * 
         * @access  protected
         * @var     Function
         */
        _events: function() {
            return Object.assign(this._super(), {

                /**
                 * deleteCollection
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                deleteCollection: function(event, $element) {
                    this.hide();
                    this._deleteCollection();
                },

                /**
                 * downloadCollection
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                downloadCollection: function(event, $element) {
                    this.hide();
                    this._downloadCollection();
                },

                /**
                 * editCollection
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                editCollection: function(event, $element) {
                    this.hide();
                    var collection = this._getCollection();
                    ModalUtils.showEdit(collection);
                }
            });
        },

        /**
         * _popperPlacement
         * 
         * @access  protected
         * @var     String (default: 'right')
         */
        _popperPlacement: 'right',

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'CollectionContextMenuPopoverComponentView')
         */
        _string: 'CollectionContextMenuPopoverComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * _deleteCollection
         * 
         * @access  protected
         * @return  Boolean
         */
        _deleteCollection: function() {
            var primary = 'Are you sure?',
                secondary = 'This cannot be undone.',
                handler = this._handleDeleteEvent.bind(this);
            UserAgentUtils.confirm(primary, secondary).then(handler);
            return true;
        },

        /**
         * _downloadCollection
         * 
         * @access  protected
         * @return  Boolean
         */
        _downloadCollection: function() {
            if (AuthUtils.feature('collectionDownloads') === false) {
                ModalUtils.showUpsell('collectionDownloads');
                return false;
            }
            var primary = 'Currently disabled',
                secondary = 'Sorry for the trouble, but this feature is temporarily disabled. Please contact support@iconduck.com for more information.';
            UserAgentUtils.alert(primary, secondary);
            return true;
        },

        /**
         * _getCollection
         * 
         * @access  protected
         * @return  CollectionActiveRecord
         */
        _getCollection: function() {
            var collection = this._data.collection;
            return collection;
        },

        /**
         * _handleDeleteEvent
         * 
         * @access  protected
         * @return  Boolean
         */
        _handleDeleteEvent: function() {
            var collection = this._getCollection();
            collection.delete();
            this._showSuccessModal();
            return true;
        },

        /**
         * _showSuccessModal
         * 
         * @access  protected
         * @return  Boolean
         */
        _showSuccessModal: function() {
            var primary = 'Collection deleted',
                secondary = 'It is no longer accessible on Iconduck';
            ModalUtils.showSuccess(primary, secondary);
            return true;
        }
    });
});
window.DependencyLoader.push(['BasePopoverComponentView'], function() {

    /**
     * DownloadPopoverComponentView
     * 
     * @extends BasePopoverComponentView
     */
    window.DownloadPopoverComponentView = BasePopoverComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _events
         * 
         * @access  protected
         * @var     Function
         */
        _events: function() {
            return Object.assign(this._super(), {

                /**
                 * download
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                download: function(event, $element) {
                    var type = $element.getAttribute('data-type'),
                        size = $element.getAttribute('data-size');
                    this._download(type, size);
                }
            });
        },

        /**
         * _popperOffset
         * 
         * @access  protected
         * @var     String (default: [0, 6])
         */
        _popperOffset: [0, 6],

        /**
         * _popperPlacement
         * 
         * @access  protected
         * @var     String (default: 'right')
         */
        _popperPlacement: 'right',

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'DownloadPopoverComponentView')
         */
        _string: 'DownloadPopoverComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * _download
         * 
         * @access  protected
         * @param   String type
         * @param   null|Number size
         * @return  Boolean
         */
        _download: function(type, size) {
            if (type === 'svg') {
                var response = this._data.vector.download('svg');
                return response;
            }
            if (type === 'zip') {
                if (AuthUtils.feature('zips') === false) {
                    ModalUtils.showUpsell('zips');
                    return false;
                }
                var response = this._data.vector.download('zip');
                return response;
            }
            size = size.toInt();
            if (size === 2048) {
                if (AuthUtils.feature('largeSizes') === false) {
                    ModalUtils.showUpsell('largeSizes');
                    return false;
                }
            }
            if (size === 4096) {
                if (AuthUtils.feature('largeSizes') === false) {
                    ModalUtils.showUpsell('largeSizes');
                    return false;
                }
            }
            var response = this._data.vector.download('png', size);
            return response;
        }
    });
});
window.DependencyLoader.push(['BasePopoverComponentView'], function() {

    /**
     * EditModalSecondaryPopoverComponentView
     * 
     * @extends BasePopoverComponentView
     */
    window.EditModalSecondaryPopoverComponentView = BasePopoverComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _popperPlacement
         * 
         * @access  protected
         * @var     String (default: 'right')
         */
        _popperPlacement: 'right',

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'EditModalSecondaryPopoverComponentView')
         */
        _string: 'EditModalSecondaryPopoverComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        }
    });
});
window.DependencyLoader.push(['BasePopoverComponentView'], function() {

    /**
     * VectorContextMenuPopoverComponentView
     * 
     * @extends BasePopoverComponentView
     */
    window.VectorContextMenuPopoverComponentView = BasePopoverComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _events
         * 
         * @access  protected
         * @var     Function
         */
        _events: function() {
            return Object.assign(this._super(), {

                /**
                 * download
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                download: function(event, $element) {
                    this._data.vector.download('svg');
                }
            });
        },

        /**
         * _popperPlacement
         * 
         * @access  protected
         * @var     String (default: 'right')
         */
        _popperPlacement: 'right',

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'VectorContextMenuPopoverComponentView')
         */
        _string: 'VectorContextMenuPopoverComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * hide
         * 
         * @access  public
         * @return  Boolean
         */
        hide: function() {
            var response = this._super();
            if (response === false) {
                return false;
            }
            __Iconduck.page.clearVectorBlockPreviewStates();
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseStateComponentView'], function() {

    /**
     * BaseAuthStateComponentView
     * 
     * @extends BaseStateComponentView
     */
    window.BaseAuthStateComponentView = BaseStateComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'BaseAuthStateComponentView')
         */
        _string: 'BaseAuthStateComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        }
    });
});
window.DependencyLoader.push(['BaseAuthStateComponentView'], function() {

    /**
     * LoginAuthStateComponentView
     * 
     * @extends BaseAuthStateComponentView
     */
    window.LoginAuthStateComponentView = BaseAuthStateComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'LoginAuthStateComponentView')
         */
        _string: 'LoginAuthStateComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        }
    });
});
window.DependencyLoader.push(['BaseAuthStateComponentView'], function() {

    /**
     * PasswordAuthStateComponentView
     * 
     * @extends BaseAuthStateComponentView
     */
    window.PasswordAuthStateComponentView = BaseAuthStateComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'PasswordAuthStateComponentView')
         */
        _string: 'PasswordAuthStateComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        }
    });
});
window.DependencyLoader.push(['BaseAuthStateComponentView'], function() {

    /**
     * SignupAuthStateComponentView
     * 
     * @extends BaseAuthStateComponentView
     */
    window.SignupAuthStateComponentView = BaseAuthStateComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'SignupAuthStateComponentView')
         */
        _string: 'SignupAuthStateComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        }
    });
});
window.DependencyLoader.push(['BaseComponentView'], function() {

    /**
     * BaseStateComponentView
     * 
     * @extends BaseComponentView
     */
    window.BaseStateComponentView = BaseComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'BaseStateComponentView')
         */
        _string: 'BaseStateComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        }
    });
});
window.DependencyLoader.push(['BaseStateComponentView'], function() {

    /**
     * BaseSettingsStateComponentView
     * 
     * @extends BaseStateComponentView
     */
    window.BaseSettingsStateComponentView = BaseStateComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _events
         * 
         * @access  protected
         * @var     Function
         */
        _events: function() {
            return Object.assign(this._super(), {

                /**
                 * submit
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                submit: function(event, $element) {
                    var form = this._getForm();
                    form.submit();
                }
            });
        },

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'BaseSettingsStateComponentView')
         */
        _string: 'BaseSettingsStateComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this._setupForm();
        },

        /**
         * _enableForm
         * 
         * @access  protected
         * @return  Boolean
         */
        _enableForm: function() {
            var form = this._getForm(),
                delay = ConfigUtils.getPublicValue('uiux', 'formModalDelay');
            DataUtils.delay(delay).then(function() {
                form.enable();
            })
            return true;
        },

        /**
         * _getForm
         * 
         * @access  protected
         * @return  BaseFormComponentView
         */
        _getForm: function() {
            var $form = this.__find('form'),
                form = $form.getView();
            return form;
        },

        /**
         * _handleFormResolvedEvent
         * 
         * @access  protected
         * @param   BaseFormComponentView form
         * @param   Object response
         * @return  Boolean
         */
        _handleFormResolvedEvent: function(form, response) {
            this._enableForm();
            return true;
        },

        /**
         * _handleFormStateChangeEvent
         * 
         * @access  protected
         * @param   String formStateKey
         * @return  Boolean
         */
        _handleFormStateChangeEvent: function(formStateKey) {
            this._setFormState(formStateKey);
            return true;
        },

        /**
         * _setupForm
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupForm: function() {
            var form = this._getForm(),
                resolvedHandler = this._handleFormResolvedEvent.bind(this),
                formStateChangeHandler = this._handleFormStateChangeEvent.bind(this);
            form.addCustomEventListener('resolved', resolvedHandler);
            form.addCustomEventListener('formState/change', formStateChangeHandler);
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseSettingsStateComponentView'], function() {

    /**
     * UpdateEmailAddressSettingsStateComponentView
     * 
     * @extends BaseSettingsStateComponentView
     */
    window.UpdateEmailAddressSettingsStateComponentView = BaseSettingsStateComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'UpdateEmailAddressSettingsStateComponentView')
         */
        _string: 'UpdateEmailAddressSettingsStateComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * _handleFormResolvedEvent
         * 
         * @access  protected
         * @param   BaseFormComponentView form
         * @param   Object response
         * @return  Boolean
         */
        _handleFormResolvedEvent: function(form, response) {
            this._super(form, response);
            this._mergePublicData(response);
            this._resetInputs();
            return true;
        },

        /**
         * _mergePublicData
         * 
         * @access  protected
         * @param   Object response
         * @return  Boolean
         */
        _mergePublicData: function(response) {
            var publicData = {},
                emailAddress = response.data.object.emailAddress,
                user = AuthUtils.getUser();
            publicData.emailAddress = emailAddress;
            user.merge(publicData);
            return true;
        },

        /**
         * _resetInputs
         * 
         * @access  protected
         * @return  Boolean
         */
        _resetInputs: function() {
            var $current = this.__find('#currentEmailAddress'),
                $emailAddress = this.__dataName('emailAddress'),
                $confirmEmailAddress = this.__dataName('confirmEmailAddress'),
                user = AuthUtils.getUser();
            $current.value = user.get('emailAddress');
            $emailAddress.value = '';
            $confirmEmailAddress.value = '';
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseSettingsStateComponentView'], function() {

    /**
     * UpdateNotificationsSettingsStateComponentView
     * 
     * @extends BaseSettingsStateComponentView
     */
    window.UpdateNotificationsSettingsStateComponentView = BaseSettingsStateComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'UpdateNotificationsSettingsStateComponentView')
         */
        _string: 'UpdateNotificationsSettingsStateComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * _handleFormResolvedEvent
         * 
         * @access  protected
         * @param   BaseFormComponentView form
         * @param   Object response
         * @return  Boolean
         */
        _handleFormResolvedEvent: function(form, response) {
            this._super(form, response);
            this._mergePublicData(response);
            return true;
        },

        /**
         * _mergePublicData
         * 
         * @access  protected
         * @param   Object response
         * @return  Boolean
         */
        _mergePublicData: function(response) {
            var publicData = {},
                receiveVectorSetWeeklyNotificationEmails = response.data.object.receiveVectorSetWeeklyNotificationEmails,
                user = AuthUtils.getUser();
            publicData.receiveVectorSetWeeklyNotificationEmails = receiveVectorSetWeeklyNotificationEmails;
            user.merge(publicData);
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseSettingsStateComponentView'], function() {

    /**
     * UpdatePasswordSettingsStateComponentView
     * 
     * @extends BaseSettingsStateComponentView
     */
    window.UpdatePasswordSettingsStateComponentView = BaseSettingsStateComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'UpdatePasswordSettingsStateComponentView')
         */
        _string: 'UpdatePasswordSettingsStateComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * _handleFormResolvedEvent
         * 
         * @access  protected
         * @param   BaseFormComponentView form
         * @param   Object response
         * @return  Boolean
         */
        _handleFormResolvedEvent: function(form, response) {
            this._super(form, response);
            this._resetInputs();
            return true;
        },

        /**
         * _resetInputs
         * 
         * @access  protected
         * @return  Boolean
         */
        _resetInputs: function() {
            var $password = this.__dataName('password'),
                $confirmPassword = this.__dataName('confirmPassword')
            $password.value = '';
            $confirmPassword.value = '';
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseTriggerComponentView'], function() {

    /**
     * AddCollectionItemsTriggerComponentView
     * 
     * @extends BaseTriggerComponentView
     */
    window.AddCollectionItemsTriggerComponentView = BaseTriggerComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'AddCollectionItemsTriggerComponentView')
         */
        _string: 'AddCollectionItemsTriggerComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this._addCollectionEventListeners();
            this._addUserSetEventListener();
            this._setDefaultSelectedState();
        },

        /**
         * _addCollectionEventListeners
         * 
         * @access  protected
         * @return  Boolean
         */
        _addCollectionEventListeners: function() {
            this._addCollectionsAddedEventListener();
            this._addCollectionsRemovedEventListener();
            return true;
        },

        /**
         * _addCollectionsAddedEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addCollectionsAddedEventListener: function() {
            var vector = this._getVector();
                handler = this._handleCollectionsAddedEvent.bind(this);
            vector.addCustomEventListener('collection/added', handler);
            return true;
        },

        /**
         * _addCollectionsRemovedEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addCollectionsRemovedEventListener: function() {
            var vector = this._getVector();
                handler = this._handleCollectionsRemovedEvent.bind(this);
            vector.addCustomEventListener('collection/removed', handler);
            return true;
        },

        /**
         * _handleCollectionsAddedEvent
         * 
         * @access  protected
         * @return  Boolean
         */
        _handleCollectionsAddedEvent: function() {
            this._setDefaultSelectedState();
            return true;
        },

        /**
         * _handleCollectionsRemovedEvent
         * 
         * @access  protected
         * @return  Boolean
         */
        _handleCollectionsRemovedEvent: function() {
            this._setDefaultSelectedState();
            return true;
        },

        /**
         * _addUserSetEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addUserSetEventListener: function() {
            var handler = this._setDefaultSelectedState.bind(this);
            __Iconduck.page.addCustomEventListenerOnce('user/set', handler);
            return true;
        },

        /**
         * _getVector
         * 
         * @access  protected
         * @return  VectorActiveRecord
         */
        _getVector: function() {
            var publicId = this.getAttribute('vector-public-id'),
                vector = FrameworkUtils.setActiveRecord(publicId, 'Vector');
            return vector;
        },

        /**
         * _handleClickEvent
         * 
         * @access  protected
         * @param   MouseEvent|PointerEvent event
         * @return  Boolean
         */
        _handleClickEvent: function(event) {

            // Guest
            var user = AuthUtils.getUser();
            if (user === null) {
                ModalUtils.showAuthPrompt('collections');
                return false;
            }

            // Show modal
            var vector = this._getVector();
            ModalUtils.showAddCollectionItems(vector);
            return true;
        },

        /**
         * _setDefaultSelectedState
         * 
         * @access  protected
         * @return  Boolean
         */
        _setDefaultSelectedState: function() {
            var user = AuthUtils.getUser();
            if (user === null) {
                return false;
            }
            var activeRecord = this._getVector(),
                collected = user.collected(activeRecord);
            this._setSelected(collected);
            return collected;
        },

        /**
         * _setSelected
         * 
         * @access  protected
         * @param   Boolean selected
         * @return  Boolean
         */
        _setSelected: function(selected) {
            if (selected === true) {
                this._updateCopy('Change collections');
                this._updateTooltip('Change collections');
                this._$element.addClass('selected');
                return true;
            }
            this._updateCopy('Add to collection');
            this._updateTooltip('Add to collection');
            this._$element.removeClass('selected');
            return true;
        },

        /**
         * _updateCopy
         * 
         * @access  protected
         * @param   String copy
         * @return  Boolean
         */
        _updateCopy: function(copy) {
            var $copy = this.__find('span.copy');
            if ($copy === null) {
                return false;
            }
            $copy.innerText = copy;
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseTriggerComponentView'], function() {

    /**
     * AddVectorSetVectorsTriggerComponentView
     * 
     * @extends BaseTriggerComponentView
     */
    window.AddVectorSetVectorsTriggerComponentView = BaseTriggerComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'AddVectorSetVectorsTriggerComponentView')
         */
        _string: 'AddVectorSetVectorsTriggerComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this._loadUppy();
        },

        /**
         * _getVectorSet
         * 
         * @access  protected
         * @return  VectorSetActiveRecord
         */
        _getVectorSet: function() {
            var publicId = this.getAttribute('vector-set-public-id'),
                vectorSet = FrameworkUtils.getActiveRecord(publicId);
            return vectorSet;
        },

        /**
         * _handleClickEvent
         * 
         * @access  protected
         * @param   MouseEvent|PointerEvent event
         * @return  Boolean
         */
        _handleClickEvent: function(event) {
            var vectorSet = this._getVectorSet();
            ModalUtils.showAddVectorSetVectors(vectorSet);
            return true;
        },
        /**
         * _loadUppy
         * 
         * @access  protected
         * @return  Boolean
         */
        _loadUppy: function() {
            var $script = document.createElement('script'),
                $head = document.querySelector('head');
            $script.src = 'https://iconduck.com/iconduck/static/vendors/source/external/uppy/v1.21.2/dist/uppy.min.js';
            $head.appendChild($script);
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseTriggerComponentView'], function() {

    /**
     * CreateVectorSetDesignerTriggerComponentView
     * 
     * @extends BaseTriggerComponentView
     */
    window.CreateVectorSetDesignerTriggerComponentView = BaseTriggerComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'CreateVectorSetDesignerTriggerComponentView')
         */
        _string: 'CreateVectorSetDesignerTriggerComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * _getVectorSet
         * 
         * @access  protected
         * @return  VectorSetActiveRecord
         */
        _getVectorSet: function() {
            var publicId = this.getAttribute('vector-set-public-id'),
                vectorSet = FrameworkUtils.getActiveRecord(publicId);
            return vectorSet;
        },

        /**
         * _handleClickEvent
         * 
         * @access  protected
         * @param   MouseEvent|PointerEvent event
         * @return  Boolean
         */
        _handleClickEvent: function(event) {
            var vectorSet = this._getVectorSet();
            ModalUtils.showCreateVectorSetDesigner(vectorSet);
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseTriggerComponentView'], function() {

    /**
     * CreateVectorSetSubsetTriggerComponentView
     * 
     * @extends BaseTriggerComponentView
     */
    window.CreateVectorSetSubsetTriggerComponentView = BaseTriggerComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'CreateVectorSetSubsetTriggerComponentView')
         */
        _string: 'CreateVectorSetSubsetTriggerComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * _getVectorSet
         * 
         * @access  protected
         * @return  VectorSetActiveRecord
         */
        _getVectorSet: function() {
            var publicId = this.getAttribute('vector-set-public-id'),
                vectorSet = FrameworkUtils.getActiveRecord(publicId);
            return vectorSet;
        },

        /**
         * _handleClickEvent
         * 
         * @access  protected
         * @param   MouseEvent|PointerEvent event
         * @return  Boolean
         */
        _handleClickEvent: function(event) {
            var vectorSet = this._getVectorSet();
            ModalUtils.showCreateVectorSetSubset(vectorSet);
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseTriggerComponentView'], function() {

    /**
     * DELETERequestTriggerComponentView
     * 
     * @extends BaseTriggerComponentView
     */
    window.DELETERequestTriggerComponentView = BaseTriggerComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _requiresConfirmation
         * 
         * @access  protected
         * @var     Boolean (default: true)
         */
        _requiresConfirmation: true,

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'DELETERequestTriggerComponentView')
         */
        _string: 'DELETERequestTriggerComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * _handleResolveEvent
         * 
         * @access  protected
         * @param   Object response
         * @return  Boolean
         */
        _handleResolveEvent: function(response) {
            ModalUtils.hideBusy();
            var reloadURL = this.getAttribute('reload-url');
            if (reloadURL === null) {
                var primary = 'You\'re all set!',
                    secondary = 'Request sent and processed.';
                ModalUtils.showSuccess(primary, secondary);
                var customEventName = 'request/resolved';
                this.triggerCustomEvent(customEventName);
                return true;
            }
            window.location.href = reloadURL;
            return true;
        },

        /**
         * _handleClickEvent
         * 
         * @todo    Route this through the relevant active record
         * @access  protected
         * @param   MouseEvent|PointerEvent event
         * @return  Boolean
         */
        _handleClickEvent: function(event) {
            ModalUtils.showBusy();
            var requestURL = this.getAttribute('request-url'),
                resolvedHandler = this._handleResolveEvent.bind(this),
                rejectedHandler = this._handleXHRRejectEvent.bind(this);
            RequestUtils.delete(requestURL).then(resolvedHandler).catch(rejectedHandler);
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseTriggerComponentView'], function() {

    /**
     * ManageVectorSetDesignersTriggerComponentView
     * 
     * @extends BaseTriggerComponentView
     */
    window.ManageVectorSetDesignersTriggerComponentView = BaseTriggerComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'ManageVectorSetDesignersTriggerComponentView')
         */
        _string: 'ManageVectorSetDesignersTriggerComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * _getVectorSet
         * 
         * @access  protected
         * @return  VectorSetActiveRecord
         */
        _getVectorSet: function() {
            var publicId = this.getAttribute('vector-set-public-id'),
                vectorSet = FrameworkUtils.getActiveRecord(publicId);
            return vectorSet;
        },

        /**
         * _handleClickEvent
         * 
         * @access  protected
         * @param   MouseEvent|PointerEvent event
         * @return  Boolean
         */
        _handleClickEvent: function(event) {
            var vectorSet = this._getVectorSet();
            ModalUtils.showManageVectorSetDesigners(vectorSet);
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseTriggerComponentView'], function() {

    /**
     * ManageVectorSetSubsetsTriggerComponentView
     * 
     * @extends BaseTriggerComponentView
     */
    window.ManageVectorSetSubsetsTriggerComponentView = BaseTriggerComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'ManageVectorSetSubsetsTriggerComponentView')
         */
        _string: 'ManageVectorSetSubsetsTriggerComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * _getVectorSet
         * 
         * @access  protected
         * @return  VectorSetActiveRecord
         */
        _getVectorSet: function() {
            var publicId = this.getAttribute('vector-set-public-id'),
                vectorSet = FrameworkUtils.getActiveRecord(publicId);
            return vectorSet;
        },

        /**
         * _handleClickEvent
         * 
         * @access  protected
         * @param   MouseEvent|PointerEvent event
         * @return  Boolean
         */
        _handleClickEvent: function(event) {
            var vectorSet = this._getVectorSet();
            ModalUtils.showManageVectorSetSubsets(vectorSet);
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseTriggerComponentView'], function() {

    /**
     * POSTRequestTriggerComponentView
     * 
     * @extends BaseTriggerComponentView
     */
    window.POSTRequestTriggerComponentView = BaseTriggerComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _requiresConfirmation
         * 
         * @access  protected
         * @var     Boolean (default: false)
         */
        _requiresConfirmation: false,

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'POSTRequestTriggerComponentView')
         */
        _string: 'POSTRequestTriggerComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this._overrideConfirmModalHeadlines();
            this._overrideRequestConfirmationProperty();
        },

        /**
         * _handleResolveEvent
         * 
         * @access  protected
         * @param   Object response
         * @return  Boolean
         */
        _handleResolveEvent: function(response) {
            ModalUtils.hideBusy();
            var reloadURL = this.getAttribute('reload-url');
            if (reloadURL === null) {
                var primary = 'You\'re all set!',
                    secondary = this.getAttribute('success-secondary') || 'Request sent and processed.';
                ModalUtils.showSuccess(primary, secondary);
                return true;
            }
            window.location.href = reloadURL;
            return true;
        },

        /**
         * _handleClickEvent
         * 
         * @todo    Route this through the relevant active record
         * @access  protected
         * @param   MouseEvent|PointerEvent event
         * @return  Boolean
         */
        _handleClickEvent: function(event) {
            ModalUtils.showBusy();
            var requestURL = this.getAttribute('request-url'),
                resolvedHandler = this._handleResolveEvent.bind(this),
                rejectedHandler = this._handleXHRRejectEvent.bind(this);
            RequestUtils.post(requestURL).then(resolvedHandler).catch(rejectedHandler);
            return true;
        },

        /**
         * _overrideConfirmModalHeadlines
         * 
         * @access  protected
         * @return  Boolean
         */
        _overrideConfirmModalHeadlines: function() {
            var confirmSecondary = this.getAttribute('confirm-secondary');
            if (confirmSecondary === null) {
                return false;
            }
            this._confirmModalHeadlines.secondary = confirmSecondary;
            return true;
        },

        /**
         * _overrideRequestConfirmationProperty
         * 
         * @access  protected
         * @return  Boolean
         */
        _overrideRequestConfirmationProperty: function() {
            var requiresConfirmation = this.getAttribute('requires-confirmation');
            if (requiresConfirmation === null) {
                return false;
            }
            requiresConfirmation = requiresConfirmation.toInt();
            this._requiresConfirmation = requiresConfirmation === 1;
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseComponentView'], function() {

    /**
     * BaseTriggerComponentView
     * 
     * @extends BaseComponentView
     */
    window.BaseTriggerComponentView = BaseComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _confirmModalHeadlines
         * 
         * @access  protected
         * @var     Object
         */
        _confirmModalHeadlines: {
            primary: 'Are you sure?',
            secondary: 'This cannot be undone.'
        },

        /**
         * _requiresConfirmation
         * 
         * @access  protected
         * @var     Boolean (default: false)
         */
        _requiresConfirmation: false,

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'BaseTriggerComponentView')
         */
        _string: 'BaseTriggerComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this._addClickEventListener();
            this._test();
        },

        /**
         * _addClickEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addClickEventListener: function() {
            var $element = this._$element,
                handler = this._handleClickEventConfirmationEvent.bind(this);
            $element.addEventListener('click', function(event) {
                event.preventDefault();
                handler(event);
            });
            return true;
        },

        /**
         * _handleClickEventConfirmationEvent
         * 
         * @access  protected
         * @param   MouseEvent|PointerEvent event
         * @return  Boolean
         */
        _handleClickEventConfirmationEvent: function(event) {
            var requiresConfirmation = this._requiresConfirmation,
                handler = this._handleClickEvent.bind(this, event);
            if (requiresConfirmation === false) {
                handler(event);
                return true;
            }
            var primary = this._confirmModalHeadlines.primary,
                secondary = this._confirmModalHeadlines.secondary;
            UserAgentUtils.confirm(primary, secondary).then(handler);
            return true;
        },

        /**
         * _handleXHRRejectEvent
         * 
         * @access  protected
         * @param   Object response
         * @return  Boolean
         */
        _handleXHRRejectEvent: function(response) {
            ModalUtils.closeVisible();
            var modal = ModalUtils.showCrash({"basename":"Base.js","line":106});
            modal.sendCrashReport();
            __Iconduck.page.kill();
            return true;
        },

        /**
         * _test
         * 
         * This method works in the following way:
         * If a test attribute is found, and evalutates to true, then it's
         * removed. Once removed, CSS kicks in and stops "hiding" it.
         * 
         * @access  protected
         * @return  Boolean
         */
        _test: function() {
            var test = this.getAttribute('test');
            if (test === null) {
                return true;
            }
            var passed = eval(test);
            if (passed === true) {
                this.removeAttribute('test')
            }
            return false;
        }
    });
});
window.DependencyLoader.push(['BaseTriggerComponentView'], function() {

    /**
     * CanvaUpgradeTriggerComponentView
     * 
     * @extends BaseTriggerComponentView
     */
    window.CanvaUpgradeTriggerComponentView = BaseTriggerComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'CanvaUpgradeTriggerComponentView')
         */
        _string: 'CanvaUpgradeTriggerComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * _handleClickEvent
         * 
         * @access  protected
         * @param   MouseEvent|PointerEvent event
         * @return  Boolean
         */
        _handleClickEvent: function(event) {
            var href = this._$element.getAttribute('href');
            window.open(href);
            window.close();
            return true;
        },

        /**
         * markup
         * 
         * @access  protected
         * @return  String
         */
        // markup: function() {
        //     return '<a href="#" clas="button">Upgrade</a>';
        // }
    });
});
window.DependencyLoader.push(['BaseTriggerComponentView'], function() {

    /**
     * ChangeVectorThumbPreviewFillColorTriggerComponentView
     * 
     * @extends BaseTriggerComponentView
     */
    window.ChangeVectorThumbPreviewFillColorTriggerComponentView = BaseTriggerComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'ChangeVectorThumbPreviewFillColorTriggerComponentView')
         */
        _string: 'ChangeVectorThumbPreviewFillColorTriggerComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * _getFillColor
         * 
         * @access  protected
         * @return  String
         */
        _getFillColor: function() {
            var fillColor = 'rgba(0, 255, 255, 1.00)';
            return fillColor;
        },

        /**
         * _getUICustomizationPropertiesCookieValue
         * 
         * @access  protected
         * @return  Object
         */
        _getUICustomizationPropertiesCookieValue: function() {
            var key = 'uiCustomizationProperties',
                properties = CookieUtils.get(key) || {};
            return properties;
        },

        /**
         * _handleClickEvent
         * 
         * @access  protected
         * @param   MouseEvent|PointerEvent event
         * @return  Boolean
         */
        _handleClickEvent: function(event) {
            this._setCookieValue();
            return true;
        },

        /**
         * _setCookieValue
         * 
         * @access  protected
         * @return  Boolean
         */
        _setCookieValue: function() {
            var properties = this._getUICustomizationPropertiesCookieValue(),
                fillColor = this._getFillColor();
            properties.vectorThumbPreviewFillColor = fillColor;
            var key = 'uiCustomizationProperties';
            CookieUtils.set(key, properties);
            this._updateBodyClass();
            return true;
        },

        /**
         * _updateBodyClass
         * 
         * @access  protected
         * @return  Boolean
         */
        _updateBodyClass: function() {
            LoadUtils.updateVectorThumbPreviewFillColors();
            return true;
        },
    });
});
window.DependencyLoader.push(['BaseTriggerComponentView'], function() {

    /**
     * ChangeVectorThumbPreviewSizeTriggerComponentView
     * 
     * @extends BaseTriggerComponentView
     */
    window.ChangeVectorThumbPreviewSizeTriggerComponentView = BaseTriggerComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'ChangeVectorThumbPreviewSizeTriggerComponentView')
         */
        _string: 'ChangeVectorThumbPreviewSizeTriggerComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * _getUICustomizationPropertiesCookieValue
         * 
         * @access  protected
         * @return  Object
         */
        _getUICustomizationPropertiesCookieValue: function() {
            var key = 'uiCustomizationProperties',
                properties = CookieUtils.get(key) || {};
            return properties;
        },

        /**
         * _handleClickEvent
         * 
         * @access  protected
         * @param   MouseEvent|PointerEvent event
         * @return  Boolean
         */
        _handleClickEvent: function(event) {
            this._setCookieValue();
            return true;
        },

        /**
         * _setCookieValue
         * 
         * @access  protected
         * @return  Boolean
         */
        _setCookieValue: function() {
            var properties = this._getUICustomizationPropertiesCookieValue(),
                size = properties.vectorThumbPreviewSize || 'small';
            if (size === 'small') {
                size = 'medium';
            }
            else if (size === 'medium') {
                size = 'large';
            }
            else if (size === 'large') {
                size = 'small';
            }
            properties.vectorThumbPreviewSize = size;
            var key = 'uiCustomizationProperties';
            CookieUtils.set(key, properties);
            this._updateBodyClass();
            return true;
        },

        /**
         * _updateBodyClass
         * 
         * @access  protected
         * @return  Boolean
         */
        _updateBodyClass: function() {
            var properties = this._getUICustomizationPropertiesCookieValue(),
                sizeLabel = properties.vectorThumbPreviewSize || 'small';
            document.body.removeClass('custom-vectorSizeSmall');
            document.body.removeClass('custom-vectorSizeMedium');
            document.body.removeClass('custom-vectorSizeLarge');
            var sizeClassNameLabel = DataUtils.ucfirst(sizeLabel),
                className = 'custom-vectorSize' + (sizeClassNameLabel);
            document.body.addClass(className);
            return true;
        },
    });
});
window.DependencyLoader.push(['BaseTriggerComponentView'], function() {

    /**
     * ContextMenuTriggerComponentView
     * 
     * @extends BaseTriggerComponentView
     */
    window.ContextMenuTriggerComponentView = BaseTriggerComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'ContextMenuTriggerComponentView')
         */
        _string: 'ContextMenuTriggerComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * _drawCollectionContextMenuPopover
         * 
         * @access  protected
         * @return  Boolean
         */
        _drawCollectionContextMenuPopover: function() {
            var templateName = 'CollectionContextMenuPopoverComponent',
                data = {};
            data.collection = this._getCollection();
            var response = this._drawPopover(templateName, data);
            return response;
        },

        /**
         * _getCollection
         * 
         * @access  protected
         * @return  CollectionActiveRecord
         */
        _getCollection: function(event) {
            var publicId = this.getAttribute('public-id'),
                collection = FrameworkUtils.setActiveRecord(publicId, 'Collection');
            return collection;
        },

        /**
         * _handleClickEvent
         * 
         * @access  protected
         * @param   MouseEvent|PointerEvent event
         * @return  Boolean
         */
        _handleClickEvent: function(event) {
            if (this.getAttribute('type') === 'editModalSecondaryPopover') {
                var popover = ModalUtils.getLastVisible().getPopover();
                popover.show();
            }
            if (this.getAttribute('type') === 'collection') {
                this._drawCollectionContextMenuPopover();
                this._setupPopover();
                this._popover.show();
            }
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseTriggerComponentView'], function() {

    /**
     * CopyURLTriggerComponentView
     * 
     * @extends BaseTriggerComponentView
     */
    window.CopyURLTriggerComponentView = BaseTriggerComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'CopyURLTriggerComponentView')
         */
        _string: 'CopyURLTriggerComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * _getVector
         * 
         * @access  protected
         * @return  VectorActiveRecord
         */
        _getVector: function() {
            var publicId = this.getAttribute('vector-public-id'),
                vector = FrameworkUtils.setActiveRecord(publicId, 'Vector');
            return vector;
        },

        /**
         * _handleClickEvent
         * 
         * @access  protected
         * @param   MouseEvent|PointerEvent event
         * @return  Boolean
         */
        _handleClickEvent: function(event) {
            var vector = this._getVector(),
                url = vector.getPNGURL(144),
                msg = 'URL copied to clipboard!';
            UserAgentUtils.copyToClipboard(url);
            NotificationUtils.showDismissGrowl(msg);
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseTriggerComponentView'], function() {

    /**
     * CreateCollectionTriggerComponentView
     * 
     * @extends BaseTriggerComponentView
     */
    window.CreateCollectionTriggerComponentView = BaseTriggerComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'CreateCollectionTriggerComponentView')
         */
        _string: 'CreateCollectionTriggerComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * _handleClickEvent
         * 
         * @access  protected
         * @param   MouseEvent|PointerEvent event
         * @return  Boolean
         */
        _handleClickEvent: function(event) {
            var modal = ModalUtils.showCreateCollection(),
                handler = this._handleModalResolvedEvent.bind(this);
            modal.addCustomEventListener('form/resolved', handler);
            return true;
        },

        /**
         * _handleModalResolvedEvent
         * 
         * @access  protected
         * @param   CollectionActiveRecord collection
         * @return  Boolean
         */
        _handleModalResolvedEvent: function(collection) {
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseTriggerComponentView'], function() {

    /**
     * EditRecordTriggerComponentView
     * 
     * @extends BaseTriggerComponentView
     */
    window.EditRecordTriggerComponentView = BaseTriggerComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'EditRecordTriggerComponentView')
         */
        _string: 'EditRecordTriggerComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * _handleClickEvent
         * 
         * @access  protected
         * @param   MouseEvent|PointerEvent event
         * @return  Boolean
         */
        _handleClickEvent: function(event) {
            if (this._invalidEditEvent() === true) {
                return false;
            }
            var activeRecord = this._getActiveRecord();
            ModalUtils.showEdit(activeRecord);
            return true;
        },

        /**
         * _getActiveRecord
         * 
         * @access  protected
         * @return  BaseActiveRecord
         */
        _getActiveRecord: function() {
            var publicId = this.getAttribute('public-id'),
                activeRecord = FrameworkUtils.getActiveRecord(publicId) || this._setActiveRecord();
            return activeRecord;
        },

        /**
         * _getActiveRecordModelName
         * 
         * @note    @onassar
         * @access  protected
         * @return  String
         */
        _getActiveRecordModelName: function() {
            var modelName = 'User',
                publicId = this.getAttribute('public-id');
            if (publicId.match(/^appl/) !== null) {
                modelName = 'Application';
            }
            if (publicId.match(/^cllc/) !== null) {
                modelName = 'Collection';
            }
            if (publicId.match(/^dsgn/) !== null) {
                modelName = 'Designer';
            }
            if (publicId.match(/^fgpl/) !== null) {
                modelName = 'FigmaPlugin';
            }
            if (publicId.match(/^lcns/) !== null) {
                modelName = 'License';
            }
            if (publicId.match(/^rdrc/) !== null) {
                modelName = 'Redirect';
            }
            if (publicId.match(/^sbst/) !== null) {
                modelName = 'Subset';
            }
            if (publicId.match(/^upgr/) !== null) {
                modelName = 'Upgrade';
            }
            if (publicId.match(/^usr0/) !== null) {
                modelName = 'User';
            }
            if (publicId.match(/^uetm/) !== null) {
                modelName = 'UserEmailTemplate';
            }
            if (publicId.match(/^vctr/) !== null) {
                modelName = 'Vector';
            }
            if (publicId.match(/^vcst/) !== null) {
                modelName = 'VectorSet';
            }
            if (publicId.match(/^vndr/) !== null) {
                modelName = 'Vendor';
            }
            return modelName;
        },

        /**
         * _invalidEditEvent
         * 
         * @access  protected
         * @param   Øbject event
         * @return  Boolean
         */
        _invalidEditEvent: function(event) {
            var activeRecord = this._getActiveRecord(),
                type = activeRecord.getActiveRecordType();
            if (type === 'FigmaPlugin') {
                if (activeRecord.get('vectorSetId').toInt() === 0) {
                    var primary = 'Cannot edit Figma Plugin',
                        secondary = 'The global Figma Plugin cannot be edited.';
                    ModalUtils.showAlert(primary, secondary);
                    return true;
                }
            }
            return false;
        },

        /**
         * _setActiveRecord
         * 
         * @note    Calling function only makes this call if the active record
         *          can't be found in memory. This only happens when the active
         *          record being searched for is in reference of a record that
         *          isn't explicitly being sent down into memory (eg. by
         *          Config\Iconduck\Site).
         * @access  protected
         * @return  BaseActiveRecord
         */
        _setActiveRecord: function() {
            var publicId = this.getAttribute('public-id'),
                name = this._getActiveRecordModelName(),
                activeRecord = FrameworkUtils.setActiveRecord(publicId, name);
            return activeRecord;
        }
    });
});
window.DependencyLoader.push(['BaseTriggerComponentView'], function() {

    /**
     * LikeTriggerComponentView
     * 
     * @extends BaseTriggerComponentView
     */
    window.LikeTriggerComponentView = BaseTriggerComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'LikeTriggerComponentView')
         */
        _string: 'LikeTriggerComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this._addUserSetEventListener();
            this._setDefaultSelectedState();
        },

        /**
         * _addUserSetEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addUserSetEventListener: function() {
            var handler = this._setDefaultSelectedState.bind(this);
            __Iconduck.page.addCustomEventListenerOnce('user/set', handler);
            return true;
        },

        /**
         * _animateHeaderIcon
         * 
         * @access  protected
         * @return  Boolean
         */
        _animateHeaderIcon: function() {
            var header = FrameworkUtils.getComponentView('HeaderBlock');
            header.pulseLikeIcon();
            return true;
        },

        /**
         * _getActiveRecord
         * 
         * @access  protected
         * @return  VectorActiveRecord|VectorSetActiveRecord
         */
        _getActiveRecord: function() {
            var vectorPublicId = this.getAttribute('vector-public-id');
            if (vectorPublicId !== null) {
                var activeRecord = FrameworkUtils.setActiveRecord(vectorPublicId, 'Vector');
                return activeRecord;
            }
            var vectorSetPublicId = this.getAttribute('vector-set-public-id'),
                activeRecord = FrameworkUtils.setActiveRecord(vectorSetPublicId, 'VectorSet');
            return activeRecord;
        },

        /**
         * _getPublicId
         * 
         * @access  protected
         * @return  String
         */
        _getPublicId: function() {
            var publicId = this.getAttribute('vector-public-id') || this.getAttribute('vector-set-public-id');
            return publicId;
        },

        /**
         * _handleClickEvent
         * 
         * @access  protected
         * @param   MouseEvent|PointerEvent event
         * @return  Boolean
         */
        _handleClickEvent: function(event) {

            // Guest
            var user = AuthUtils.getUser();
            if (user === null) {
                ModalUtils.showAuthPrompt('likes');
                return false;
            }

            // Remove the like
            var activeRecord = this._getActiveRecord(),
                liked = user.liked(activeRecord);
            if (liked === true) {
                this._setSelected(false);
                activeRecord.unlike();
                __Iconduck.page.triggerCustomEvent('likes/removed', [this]);
                return false;
            }

            // Create the like
            this._setSelected(true);
            activeRecord.like();
            this._animateHeaderIcon();
            NotificationUtils.showFirstLikeGrowl();
            return false;
        },

        /**
         * _setDefaultSelectedState
         * 
         * @access  protected
         * @return  Boolean
         */
        _setDefaultSelectedState: function() {
            var user = AuthUtils.getUser();
            if (user === null) {
                return false;
            }
            var activeRecord = this._getActiveRecord(),
                liked = user.liked(activeRecord);
            this._setSelected(liked);
            return liked;
        },

        /**
         * _setSelected
         * 
         * @access  protected
         * @param   Boolean selected
         * @return  Boolean
         */
        _setSelected: function(selected) {
            if (selected === true) {
                this._updateCopy('Unlike');
                this._updateTooltip('Unlike');
                this._$element.addClass('selected');
                return true;
            }
            this._updateCopy('Like');
            this._updateTooltip('Like');
            this._$element.removeClass('selected');
            return true;
        },

        /**
         * _updateCopy
         * 
         * @access  protected
         * @param   String copy
         * @return  Boolean
         */
        _updateCopy: function(copy) {
            var $copy = this.__find('span.copy');
            if ($copy === null) {
                return false;
            }
            $copy.innerText = copy;
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseTriggerComponentView'], function() {

    /**
     * LoaderTriggerComponentView
     * 
     * @extends BaseTriggerComponentView
     */
    window.LoaderTriggerComponentView = BaseTriggerComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _loading
         * 
         * @access  protected
         * @var     Boolean (default: false)
         */
        _loading: false,

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'LoaderTriggerComponentView')
         */
        _string: 'LoaderTriggerComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
            this._setupVectorGroup();
        },

        /**
         * _appendQueryParams
         * 
         * @access  protected
         * @param   Object payload
         * @return  Boolean
         */
        _appendQueryParams: function(payload) {
            var params = this._getParams();
            if (params === null) {
                return false;
            }
            var keys = Object.keys(params);
            for (var key of keys) {
                payload[key] = params[key]
            }
            return true;
        },

        /**
         * _cleanPayload
         * 
         * @access  protected
         * @param   Object payload
         * @return  Object
         */
        _cleanPayload: function(payload) {
            for (var key in payload) {
                var value = payload[key];
                if (value === null || value === undefined) {
                    delete payload[key];
                }
            }
            return payload;
        },

        /**
         * _disableAnchor
         * 
         * @access  protected
         * @return  void
         */
        _disableAnchor: function() {
            var $anchor = this._getTriggerElement();
            $anchor.disable();
        },

        /**
         * _enableAnchor
         * 
         * @access  protected
         * @return  void
         */
        _enableAnchor: function() {
            var $anchor = this._getTriggerElement();
            $anchor.removeAttribute('disabled');
        },

        /**
         * _getEndpoint
         * 
         * @access  protected
         * @return  String
         */
        _getEndpoint: function() {
            var endpoint = this.getAttribute('endpoint');
            return endpoint;
        },

        /**
         * _getLimit
         * 
         * @access  protected
         * @return  Number
         */
        _getLimit: function() {
            var limit = this.getAttribute('limit').toInt();
            return limit;
        },

        /**
         * _getOffset
         * 
         * @access  protected
         * @return  Number
         */
        _getOffset: function() {
            var offset = this.getAttribute('offset').toInt();
            return offset;
        },

        /**
         * _getPayload
         * 
         * @access  protected
         * @return  Object
         */
        _getPayload: function() {
            var payload = {};
            payload.key = ConfigUtils.getPublicValue('security', 'apiKey');
            payload.limit = this._getLimit();
            payload.offset = this._getOffset();
            payload.query = this._getQuery();
            this._appendQueryParams(payload);
            return payload;
        },

        /**
         * _getParams
         * 
         * @access  protected
         * @return  null|Object
         */
        _getParams: function() {
            var params = this.getAttribute('params');
            if (params === null) {
                return null;
            }
            params = JSON.parse(params);
            return params;
        },

        /**
         * _getQuery
         * 
         * @access  protected
         * @return  String
         */
        _getQuery: function() {
            var query = this.getAttribute('query');
            return query;
        },

        /**
         * _getTriggerElement
         * 
         * @access  protected
         * @return  HTMLElement
         */
        _getTriggerElement: function() {
            var $element = this._$element,
                $anchor = $element.querySelector('a');
            return $anchor;
        },

        /**
         * _getVectorGroupBlockComponentElement
         * 
         * @access  protected
         * @return  HTMLElement
         */
        _getVectorGroupBlockComponentElement: function() {
            var $previous = this._$element.previousElementSibling,
                selector = '[data-component-name="VectorGroupBlock"]',
                $component = $previous.querySelector(selector);
            return $component;
        },

        /**
         * _getVectors
         * 
         * @access  protected
         * @return  VectorsCollection
         */
        _getVectors: function() {
            var $component = __Iconduck.page.__find('[data-component-loader="1"]'),
                vectorGroupBlock = $component.getView(),
                vectors = vectorGroupBlock.getVectors();
            return vectors;
        },

        /**
         * _handleClickEvent
         * 
         * @access  protected
         * @param   MouseEvent|PointerEvent event
         * @return  Promise
         */
        _handleClickEvent: function(event) {
            var $target = event.target,
                $anchor = this.__find('a');
            if ($target === $anchor) {
                var promise = this.loadMore();
                return promise;
            }
            var promise = DataUtils.getPromise(null);
            return promise;
        },

        /**
         * _handleSuccessfulRequest
         * 
         * @note    Ordered
         * @access  protected
         * @param   Object response
         * @return  Array
         */
        _handleSuccessfulRequest: function(response) {
            this._loading = false;
            this._updateComponentAttributes(response);
            this._enableAnchor();
            var activeRecords = this._mapVectors(response);
            this._removeElement(response);
            return activeRecords;
        },

        /**
         * _mapVectors
         * 
         * @access  protected
         * @param   Object response
         * @return  Array
         */
        _mapVectors: function(response) {
            var dataSet = response.data.objects,
                more = response.meta.more,
                vectors = this._getVectors(),
                activeRecords = vectors.map(dataSet);
            vectors.setMore(more);
            return activeRecords;
        },

        /**
         * _removeElement
         * 
         * @access  protected
         * @param   Object response
         * @return  void
         */
        _removeElement: function(response) {
            var meta = response.meta,
                more = meta.more;
            if (more === true) {
                return false;
            }
            var $component = this._getVectorGroupBlockComponentElement();
            $component.addClass('loaded');
            var $element = this._$element;
            $element.remove();
            return true;
        },

        /**
         * _setOffset
         * 
         * @access  protected
         * @param   Number offset
         * @return  void
         */
        _setOffset: function(offset) {
            this.setAttribute('offset', offset);
        },

        /**
         * _setupVectorGroup
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupVectorGroup: function() {
            var component = FrameworkUtils.getComponentView('VectorGroupBlock');
            if (component === null) {
                return false;
            }
            component.setLoader(this);
            return true;
        },

        /**
         * _updateComponentAttributes
         * 
         * @access  protected
         * @param   Object response
         * @return  void
         */
        _updateComponentAttributes: function(response) {
            this._updateOffsetAttribute(response);
        },

        /**
         * _updateOffsetAttribute
         * 
         * @access  protected
         * @param   Object response
         * @return  void
         */
        _updateOffsetAttribute: function(response) {
            var offset = this._getOffset(),
                objects = response.data.objects;
            offset = (offset) + objects.length;
            this._setOffset(offset);
        },

        /**
         * loadMore
         * 
         * @access  public
         * @return  Promise
         */
        loadMore: function() {
            this._loading = true;
            this._disableAnchor();
            var endpoint = this._getEndpoint(),
                payload = this._getPayload(),
                payload = this._cleanPayload(payload),
                handler = this._handleSuccessfulRequest.bind(this),
                promise = RequestUtils.get(endpoint, payload).then(handler);
            return promise;
        },

        /**
         * loading
         * 
         * @access  public
         * @return  Boolean
         */
        loading: function() {
            var loading = this._loading;
            return loading;
        }
    });
});
window.DependencyLoader.push(['BaseTriggerComponentView'], function() {

    /**
     * OpenWithFigmaTriggerComponentView
     * 
     * @extends BaseTriggerComponentView
     */
    window.OpenWithFigmaTriggerComponentView = BaseTriggerComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'OpenWithFigmaTriggerComponentView')
         */
        _string: 'OpenWithFigmaTriggerComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * _getVector
         * 
         * @access  protected
         * @return  VectorActiveRecord
         */
        _getVector: function() {
            var publicId = this.getAttribute('vector-public-id'),
                vector = FrameworkUtils.setActiveRecord(publicId, 'Vector');
            return vector;
        },

        /**
         * _handleClickEvent
         * 
         * @access  protected
         * @param   MouseEvent|PointerEvent event
         * @return  Boolean
         */
        _handleClickEvent: function(event) {
            var vector = this._getVector();
            ModalUtils.showOpenWithFigma(vector);
            return true;
        }
    });
});
window.DependencyLoader.push(['BaseTriggerComponentView'], function() {

    /**
     * ShareTriggerComponentView
     * 
     * @extends BaseTriggerComponentView
     */
    window.ShareTriggerComponentView = BaseTriggerComponentView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'ShareTriggerComponentView')
         */
        _string: 'ShareTriggerComponentView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @param   Object data
         * @return  void
         */
        init: function($element, data) {
            this._super($element, data);
        },

        /**
         * _getText
         * 
         * @access  protected
         * @return  String
         */
        _getText: function() {
            var vector = this._getVector(),
                name = vector.getName(),
                text = 'Download the "' + (name) + '" icon';
            return text;
        },

        /**
         * _getTitle
         * 
         * @access  protected
         * @return  String
         */
        _getTitle: function() {
            var vector = this._getVector(),
                title = 'Iconduck';
            return title;
        },

        /**
         * _getURL
         * 
         * @access  protected
         * @return  String
         */
        _getURL: function() {
            var vector = this._getVector(),
                url = vector.getURL();
            url = (url) + '?shared';
            return url;
        },

        /**
         * _getVector
         * 
         * @access  protected
         * @return  VectorActiveRecord
         */
        _getVector: function() {
            var publicId = this.getAttribute('vector-public-id'),
                vector = FrameworkUtils.setActiveRecord(publicId, 'Vector');
            return vector;
        },

        /**
         * _handleClickEvent
         * 
         * @access  protected
         * @param   MouseEvent|PointerEvent event
         * @return  Boolean
         */
        _handleClickEvent: function(event) {
            var data = {};
            data.title = this._getTitle();
            data.text = this._getText();
            data.url = this._getURL();
            var promise = window.navigator.share(data),
                resolved = this._handleResolved.bind(this),
                rejected = this._handleRejected.bind(this);
            promise.then(resolved).catch(rejected);
            return true;
        },

        /**
         * _handleRejected
         * 
         * @see     https://developer.mozilla.org/en-US/docs/Web/API/Navigator/share
         * @access  protected
         * @return  Boolean
         */
        _handleRejected: function() {
            return true;
        },

        /**
         * _handleResolved
         * 
         * @see     https://developer.mozilla.org/en-US/docs/Web/API/Navigator/share
         * @access  protected
         * @return  Boolean
         */
        _handleResolved: function() {
            var primary = 'Way to go!',
                secondary = 'Thanks for sharing Iconduck!';
            ModalUtils.showSuccess(primary, secondary);
            return true;
        },
    });
});
window.DependencyLoader.push(['BaseView'], function() {

    /**
     * BasePageView
     * 
     * @fires   auth/login
     * @fires   auth/logout
     * @fires   config/admin/loaded
     * @fires   user/set
     * @fires   user/set/admin
     * @extends BaseView
     */
    window.BasePageView = BaseView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _dead
         * 
         * @access  protected
         * @var     Boolean (default: false)
         */
        _dead: false,

        /**
         * _designers
         * 
         * @access  protected
         * @var     null|DesignersCollection (default: null)
         */
        _designers: null,

        /**
         * _figmaPlugins
         * 
         * @access  protected
         * @var     null|FigmaPluginsCollection (default: null)
         */
        _figmaPlugins: null,

        /**
         * _images
         * 
         * @access  protected
         * @var     Array (default: [])
         */
        _images: [],

        /**
         * _licenses
         * 
         * @access  protected
         * @var     null|LicensesCollection (default: null)
         */
        _licenses: null,

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'BasePageView')
         */
        _string: 'BasePageView',

        /**
         * _subsets
         * 
         * @access  protected
         * @var     null|SubsetsCollection (default: null)
         */
        _subsets: null,

        /**
         * _vectorSets
         * 
         * @access  protected
         * @var     null|VectorSetsCollection (default: null)
         */
        _vectorSets: null,

        /**
         * _vendors
         * 
         * @access  protected
         * @var     null|VendorsCollection (default: null)
         */
        _vendors: null,

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @see     https://docs.sentry.io/platforms/javascript/configuration/filtering/
         * @see     https://docs.sentry.io/platforms/javascript/configuration/options/#before-send
         * @note    Ordered
         * @note    _setupWindowReferences should be first to ensure global
         *          singleton access to view (e.g. __Iconduck.page). _super
         *          should be second.
         * @access  public
         * @param   HTMLElement $element
         * @return  void
         */
        init: function($element) {
            NativeUtils.init();
            UserAgentUtils.init();
            this._setupWindowReferences();
            this._super($element);
            this._addAdminUserSetEventListener();
            this._addUserSetEventListener();
            StateUtils.trackInitialState();
            StateUtils.addPopStateEventListener();
            this._addButtonSpaceKeyDownEventListener();
            this._addEscapeKeyDownEventListener();
            this._addSpotlightKeyDownEventListener();
            this._addEscapableElementClickEventListener();
            this._addActiveVectorComponentKeyDownEventListener();
            this._preloadImages();
            this._setupUser();
            RemoteURLOpener.init();
            RemoteURLOpener.setRef('www.iconduck.com');
            // SpellChecker.init();
        },

        /**
         * _addAdminUserSetEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addAdminUserSetEventListener: function() {
            var handler = this._handleAdminUserSetEvent.bind(this);
            __Iconduck.page.addCustomEventListenerOnce('user/set/admin', handler);
            return true;
        },

        /**
         * _addUserSetEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addUserSetEventListener: function() {
            var handler = this._handleUserSetEvent.bind(this);
            __Iconduck.page.addCustomEventListenerOnce('user/set', handler);
            return true;
        },

        /**
         * _addActiveVectorComponentKeyDownEventListener
         * 
         * Put this here rather than in the VectorComponentView for performance
         * reasons (don't want to keep adding an event).
         * 
         * @see     https://sentry.io/organizations/iconduck/issues/3654248790
         * @access  protected
         * @return  Boolean
         */
        _addActiveVectorComponentKeyDownEventListener: function() {
            var handler = this._handleActiveVectorComponentKeyDownEvent.bind(this);
            window.addEventListener('keydown', function(event) {
                if (AuthUtils.admin() === false) {
                    return false;
                }
                var code = event.code || '';
                code = code.toLowerCase();
                if (event.metaKey === true) {
                    return false;
                }
                if (event.shiftKey === true) {
                    return false;
                }
                if (code === 'keyb' || code === 'keyc' || code === 'keyd' || code === 'keye' || code === 'keyf' || code === 'keys') {
                    handler(event);
                }
            });
            return true;
        },

        /**
         * _addButtonSpaceKeyDownEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addButtonSpaceKeyDownEventListener: function() {
            var handler = this._handleSpaceButtonKeyDownEventListener.bind(this);
            window.addEventListener('keydown', handler);
            return true;
        },

        /**
         * _addEscapableElementClickEventListener
         * 
         * @access  protected
         * @return  void
         */
        _addEscapableElementClickEventListener: function() {
            var handler = this._handleEscapableElementClickEvent.bind(this);
            // window.addEventListener('click', handler, true);
            window.addEventListener('mousedown', handler, true);
        },

        /**
         * _addEscapeKeyDownEventListener
         * 
         * @access  protected
         * @return  void
         */
        _addEscapeKeyDownEventListener: function() {
            var handler = this._handleEscapeKeyDownEvent.bind(this);
            window.addEventListener('keydown', handler, true);
        },

        /**
         * _addSpotlightKeyDownEventListener
         * 
         * @access  protected
         * @return  void
         */
        _addSpotlightKeyDownEventListener: function() {
            var handler = this._handleSpotlightKeyDownEvent.bind(this);
            window.addEventListener('keydown', handler, true);
        },

        /**
         * _handleActiveVectorComponentKeyDownEvent
         * 
         * @access  protected
         * @param   Object event
         * @return  Boolean
         */
        _handleActiveVectorComponentKeyDownEvent: function(event) {
            var vector = this.getProperty('activeVector');
            if (vector === null || vector === undefined) {
                return false;
            }
            var $target = event.target;
            if ($target.form !== undefined) {
                return false;
            }

            // Edit attempt (read handled there)
            var key = event.key;
            if (key === 'e') {
                ModalUtils.showEdit(vector);
                return true;
            }

            // Map of keys to toggle column keys
            var map = {};
            map.b = 'broken';
            map.c = 'color';
            map.d = 'displayShowContrast';
            map.f = 'flagged';
            map.s = 'solid';

            // Toggle column attempt
            vector.read().then(function(activeRecord) {
                var columnKey = map[key];
                activeRecord.toggleColumn(columnKey);
                var msg = 'Toggled the property "' + (columnKey) + '"';
                NotificationUtils.showSimpleGrowl(msg, 1250);
            });
            return true;
        },

        /**
         * _handleAdminUserSetEvent
         * 
         * @access  protected
         * @return  Boolean
         */
        _handleAdminUserSetEvent: function() {
            Iconduck.loadAdminConfig();
            __Iconduck.page.addCustomEventListenerOnce('config/admin/loaded', function() {
                __Iconduck.page._$element.addAttributeValue('data-roles', 'admin');
            });
            return true;
        },

        /**
         * _handleEscapeKeyDownEvent
         * 
         * @access  protected
         * @param   Object event
         * @return  Boolean
         */
        _handleEscapeKeyDownEvent: function(event) {
            var response = ElementHideStackUtils.attempt(event);
            return response;
        },

        /**
         * _handleEscapableElementClickEvent
         * 
         * @access  protected
         * @param   Object event
         * @return  Boolean
         */
        _handleEscapableElementClickEvent: function(event) {
            var response = ElementHideStackUtils.attempt(event);
            return response;
        },

        /**
         * _handleSpaceButtonKeyDownEventListener
         * 
         * @see     https://sentry.io/organizations/iconduck/issues/3654248790
         * @access  protected
         * @param   Object event
         * @return  Boolean
         */
        _handleSpaceButtonKeyDownEventListener: function(event) {
            var code = event.code || '';
            code = code.toLowerCase();
            if (code === 'space') {
                var $target = event.target;
                if ($target === null) {
                    return false;
                }
                if ($target === undefined) {
                    return false;
                }
                if ($target.classList.contains('button') === true) {
                    event.preventDefault();
                    $target.click();
                }
            }
            return true;
        },

        /**
         * _handleSpotlightKeyDownEvent
         * 
         * @note    Spotlight check is done since it's possible that the data
         *          isn't available when the user triggers the hotkey.
         * @access  protected
         * @param   Object event
         * @return  Boolean
         */
        _handleSpotlightKeyDownEvent: function(event) {
            var code = event.code || '';
            code = code.toLowerCase();
            if (event.metaKey === true && code === 'keyk') {
                this._setupSpotlight();
                var spotlight = ModalUtils.getSpotlight();
                if (spotlight === null) {
                    return false;
                }
                var showing = spotlight.toggle();
                if (showing === true) {
                    spotlight.setState('default');
                    spotlight.next();
                    spotlight.resetSearchInput();
                }
                return true;
            }
            return false;
        },

        /**
         * _handleUserSetEvent
         * 
         * @access  protected
         * @return  Boolean
         */
        _handleUserSetEvent: function() {
            __Iconduck.page._$element.setAttribute('data-roles', 'user');
            return true;
        },

        /**
         * _preloadImages
         * 
         * @access  protected
         * @return  Boolean
         */
        _preloadImages: function() {
            var offline = ConfigUtils.getPublicValue('uiux').offline;
            if (offline === true) {
                return false;
            }
            var images = this._images;
            for (var path of images) {
                RequestUtils.loadImage(path);
            }
            return true;
        },

        /**
         * _setupSpotlight
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupSpotlight: function() {
            var modal = ModalUtils.getSpotlight();
            if (modal === null) {
                var modal = ModalUtils.showSpotlight();
                modal.hide();
                return true;
            }
            return true;
        },

        /**
         * _setupUser
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupUser: function() {
            var tokenPublicId = CookieUtils.get('token.publicId', 'server');
            if (tokenPublicId === undefined) {
                return false;
            }
            var path = '/api/v2/tokens/' + (tokenPublicId);
            RequestUtils.get(path).then(function(response) {
                var model = FrameworkUtils.getModel('User'),
                    publicData = response.data.object.user,
                    user = model.setActiveRecord(publicData);
                AuthUtils.setUser(user);
            }).catch(function(response) {
            });
            return true;
        },

        /**
         * _setupWindowReferences
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupWindowReferences: function() {
            window.__Iconduck.page = this;
            return true;
        },

        /**
         * clearVectorBlockPreviewStates
         * 
         * @access  public
         * @return  Boolean
         */
        clearVectorBlockPreviewStates: function() {
            var $elements = this.__find('.vector.preview') || [];
            $elements.removeClass('preview');
            return true;
        },

        /**
         * dead
         * 
         * @access  public
         * @return  Boolean
         */
        dead: function() {
            var dead = this._dead;
            return dead;
        },

        /**
         * getDesigners
         * 
         * @access  public
         * @return  DesignersCollection
         */
        getDesigners: function() {
            var designers = this._designers;
            return designers;
        },

        /**
         * getFigmaPlugins
         * 
         * @access  public
         * @return  FigmaPluginsCollection
         */
        getFigmaPlugins: function() {
            var figmaPlugins = this._figmaPlugins;
            return figmaPlugins;
        },

        /**
         * getLicenses
         * 
         * @access  public
         * @return  LicensesCollection
         */
        getLicenses: function() {
            var licenses = this._licenses;
            return licenses;
        },

        /**
         * getSubsets
         * 
         * @access  public
         * @return  SubsetsCollection
         */
        getSubsets: function() {
            var subsets = this._subsets;
            return subsets;
        },

        /**
         * getVectorSets
         * 
         * @access  public
         * @return  VectorSetsCollection
         */
        getVectorSets: function() {
            var vectorSets = this._vectorSets;
            return vectorSets;
        },

        /**
         * getVendors
         * 
         * @access  public
         * @return  VendorsCollection
         */
        getVendors: function() {
            var vendors = this._vendors;
            return vendors;
        },

        /**
         * hideAccountPopover
         * 
         * @access  public
         * @return  Boolean
         */
        hideAccountPopover: function() {
            var headerBlock =__Iconduck.page.getComponent('HeaderBlock'),
                accountPopover = headerBlock.getAccountPopover(),
                response = accountPopover.hide();
            return response;
        },

        /**
         * kill
         * 
         * @access  public
         * @return  Boolean
         */
        kill: function() {
            this._dead = true;
            return true;
        },

        /**
         * setupAdminCollections
         * 
         * @access  public
         * @return  Boolean
         */
        setupAdminCollections: function() {
            var designers = ConfigUtils.getAdminValue('collections', 'designers'),
                figmaPlugins = ConfigUtils.getAdminValue('collections', 'figmaPlugins'),
                subsets = ConfigUtils.getAdminValue('collections', 'subsets'),
                vendors = ConfigUtils.getAdminValue('collections', 'vendors');
            this._designers = new DesignersCollection(designers);
            this._figmaPlugins = new FigmaPluginsCollection(figmaPlugins);
            this._subsets = new SubsetsCollection(subsets);
            this._vendors = new VendorsCollection(vendors);
            return true;
        },

        /**
         * setupPublicCollections
         * 
         * @note    Ordered
         * @note    Because license public data is excluded from vector sets
         *          (other than the publicId), it's important that license
         *          active records get setup before vector sets do.
         * @access  public
         * @return  Boolean
         */
        setupPublicCollections: function() {
            var licenses = ConfigUtils.getPublicValue('collections', 'licenses'),
                vectorSets = ConfigUtils.getPublicValue('collections', 'vectorSets');
            this._licenses = new LicensesCollection(licenses);
            this._vectorSets = new VectorSetsCollection(vectorSets);
            return true;
        }
    });
});
window.DependencyLoader.push(['BasePageView'], function() {

    /**
     * CollectionPageView
     * 
     * @extends BasePageView
     */
    window.CollectionPageView = BasePageView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _events
         * 
         * @access  protected
         * @var     Function
         */
        _events: function() {
            return Object.assign(this._super(), {

                /**
                 * downloadCollection
                 * 
                 * @access  protected
                 * @param   Object event
                 * @param   HTMLElement $element
                 * @return  void
                 */
                downloadCollection: function(event, $element) {
                    this._downloadCollection();
                }
            });
        },

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'CollectionPageView')
         */
        _string: 'CollectionPageView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @return  void
         */
        init: function($element) {
            this._super($element);
        },

        /**
         * _downloadCollection
         * 
         * @access  protected
         * @return  Boolean
         */
        _downloadCollection: function() {
            if (AuthUtils.feature('collectionDownloads') === false) {
                ModalUtils.showUpsell('collectionDownloads');
                return false;
            }
            var primary = 'Currently disabled',
                secondary = 'Sorry for the trouble, but this feature is temporarily disabled. Please contact support@iconduck.com for more information.';
            UserAgentUtils.alert(primary, secondary);
            return true;
        },
    });
});
window.DependencyLoader.push(['BasePageView'], function() {

    /**
     * CollectionsPageView
     * 
     * @extends BasePageView
     */
    window.CollectionsPageView = BasePageView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'CollectionsPageView')
         */
        _string: 'CollectionsPageView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @return  void
         */
        init: function($element) {
            this._super($element);
            var handler = this._addRemoveEventListener.bind(this);
            __Iconduck.page.addCustomEventListenerOnce('user/set', handler);
        },

        /**
         * _addRemoveEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addRemoveEventListener: function(event) {
            var collections = this._getCollections(),
                handler = this._handleRemoveEvent.bind(this);
            collections.addCustomEventListener('remove', handler);
            return true;
        },

        /**
         * _getCollections
         * 
         * @access  protected
         * @return  CollectionsCollection
         */
        _getCollections: function(event) {
            var user = AuthUtils.getUser(),
                collections = user.getCollections();
            return collections;
        },

        /**
         * _handleRemoveEvent
         * 
         * @access  protected
         * @return  Boolean
         */
        _handleRemoveEvent: function() {
            var collections = this._getCollections(),
                length = collections.created().length,
                $empty = this.__find('.empty'),
                $groupBlock = this.__find('[data-component-name="CollectionGroupBlock"]');
            if (length === 0) {
                $empty.removeClass('display-none');
                $groupBlock.addClass('display-none');
                return true;
            }
            $empty.addClass('display-none');
            $groupBlock.removeClass('display-none');
            return true;
        }
    });
});
window.DependencyLoader.push(['BasePageView'], function() {

    /**
     * LikesPageView
     * 
     * @extends BasePageView
     */
    window.LikesPageView = BasePageView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'LikesPageView')
         */
        _string: 'LikesPageView',

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @return  void
         */
        init: function($element) {
            this._super($element);
            var handler = this._addLikeEventListener.bind(this);
            __Iconduck.page.addCustomEventListenerOnce('user/set', handler);
            var handler = this._addUnlikeEventListener.bind(this);
            __Iconduck.page.addCustomEventListenerOnce('user/set', handler);
        },

        /**
         * _addLikeEventListener
         * 
         * @access  protected
         * @return  void
         */
        _addLikeEventListener: function() {
            var likes = this._getUserLikesCollectionItemsCollection(),
                handler = this._handleLikeEventListener.bind(this);
            likes.addCustomEventListener('add', function(item) {
                handler(item);
            });
            return true;
        },

        /**
         * _addUnlikeEventListener
         * 
         * @access  protected
         * @return  void
         */
        _addUnlikeEventListener: function() {
            var likes = this._getUserLikesCollectionItemsCollection(),
                handler = this._handleUnlikeEventListener.bind(this);
            likes.addCustomEventListener('remove', function(item) {
                handler(item);
            });
            return true;
        },

        /**
         * _getUserLikesCollectionItemsCollection
         * 
         * @access  protected
         * @return  CollectionItemsCollection
         */
        _getUserLikesCollectionItemsCollection: function() {
            var user = AuthUtils.getUser(),
                likes = user.getLikes().getCollectionItems();
            return likes;
        },

        /**
         * _handleLikeEventListener
         * 
         * @access  protected
         * @param   BaseActiveRecord activeRecord
         * @return  Boolean
         */
        _handleLikeEventListener: function(activeRecord) {
            var path = '/likes';
            NotificationUtils.showReloadGrowl(path);
            return true;
        },

        /**
         * _handleUnlikeEventListener
         * 
         * @access  protected
         * @param   BaseActiveRecord activeRecord
         * @return  Boolean
         */
        _handleUnlikeEventListener: function(activeRecord) {
            var type = activeRecord.getActiveRecordType();
            if (type === 'Vector') {
                var response = this._handleVectorCollectionItemRemoveEvent(activeRecord);
                return response;
            }
            if (type === 'VectorSet') {
                var response = this._handleVectorSetCollectionItemRemoveEvent(activeRecord);
                return response;
            }
            return true;
        },

        /**
         * _handleVectorCollectionItemRemoveEvent
         * 
         * @access  protected
         * @param   BaseActiveRecord activeRecord
         * @return  Boolean
         */
        _handleVectorCollectionItemRemoveEvent: function(activeRecord) {
            var path = '/likes';
            NotificationUtils.showReloadGrowl(path);
            return true;
        },

        /**
         * _handleVectorSetCollectionItemRemoveEvent
         * 
         * @access  protected
         * @param   BaseActiveRecord activeRecord
         * @return  Boolean
         */
        _handleVectorSetCollectionItemRemoveEvent: function(activeRecord) {
            var publicId = activeRecord.get('publicId'),
                $vectorSetBlock = this.__find('[data-public-id="' + (publicId) + '"]'),
                likes = this._getUserLikesCollectionItemsCollection();
            $vectorSetBlock.data.view.destroy();
            if (likes.vectorSets().length === 0) {
                var $vectorSetGroupBlock = this.__find('[data-component-name="VectorSetGroupBlock"]');
                $vectorSetGroupBlock.addClass('display-none');
                var $empty = this.__find('[data-component-name="VectorSetGroupBlock"] + .block.clearfix.empty');
                $empty.removeClass('display-none');
            }
            return true;
        }
    });
});
window.DependencyLoader.push(['BasePageView'], function() {

    /**
     * VectorPageView
     * 
     * @extends BasePageView
     */
    window.VectorPageView = BasePageView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _$downloadPopover
         * 
         * @access  protected
         * @var     null|HTMLElement (default: null)
         */
        _$downloadPopover: null,

        /**
         * _downloadPopover
         * 
         * @access  protected
         * @var     null|DownloadPopoverComponentView (default: null)
         */
        _downloadPopover: null,

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'VectorPageView')
         */
        _string: 'VectorPageView',

        /**
         * _vector
         * 
         * @access  protected
         * @var     null|VectorActiveRecord
         */
        _vector: null,

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @return  void
         */
        init: function($element) {
            this._super($element);
            this._addContextMenuEventListener();
            this._addDownloadClickEventListener();
            this._setupVector();
            this._setupThumbZoom();
            this._drawDownloadPopover();
            this._setupDownloadPopover();
        },

        /**
         * _addContextMenuEventListener
         * 
         * @access  protected
         * @return  void
         */
        _addContextMenuEventListener: function() {
            var $elements = this.__find('[data-component-name="SizePreview"] .thumbnails img', true);
            $elements.addEventListener('contextmenu', function(event) {
                event.preventDefault();
            });
        },

        /**
         * _addDownloadClickEventListener
         * 
         * @access  protected
         * @return  void
         */
        _addDownloadClickEventListener: function() {
            var $button = this._getDownloadButtonElement(),
                handler = this._handleDownloadClickEvent.bind(this);
            $button.addEventListener('click', function(event) {
                event.preventDefault();
                handler();
            });
        },

        /**
         * _drawDownloadPopover
         * 
         * @access  protected
         * @return  Boolean
         */
        _drawDownloadPopover: function() {
            var templateName = 'DownloadPopoverComponent',
                data = this._getDownloadPopoverData(),
                $downloadPopover = ElementUtils.renderTemplate(templateName, data),
                $parent = this.__find('body');
            $parent.append($downloadPopover);
            this._$downloadPopover = $downloadPopover;
            return true;
        },

        /**
         * _getDownloadButtonElement
         * 
         * @access  protected
         * @return  HTMLElement
         */
        _getDownloadButtonElement: function() {
            var $button = this.__find('div.focus div.actions div.button-group .button.primary');
            return $button;
        },

        /**
         * _getDownloadPopoverData
         * 
         * @access  protected
         * @return  Object
         */
        _getDownloadPopoverData: function() {
            var data = {};
            data.vector = this._vector;
            return data;
        },

        /**
         * _handleDownloadClickEvent
         * 
         * @access  protected
         * @return  void
         */
        _handleDownloadClickEvent: function() {
            this._vector.download('svg');
        },

        /**
         * _setupDownloadPopover
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupDownloadPopover: function() {
            var $downloadPopover = this._$downloadPopover,
                downloadPopover = $downloadPopover.data.view,
                $reference = this.__lookup('vectorSecondary');
            downloadPopover.setupPopper($reference);
            this._downloadPopover = downloadPopover;
            return true;
        },

        /**
         * _setupVector
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupVector: function() {
            var publicData = window.__Iconduck.publicData.vector,
                model = FrameworkUtils.getModel('Vector');
            this._vector = model.setActiveRecord(publicData);
            return true;
        },

        /**
         * _setupThumbZoom
         * 
         * @see     https://github.com/imgix/drift#basic-usage
         * @access  protected
         * @return  Boolean
         */
        _setupThumbZoom: function() {
            if (UserAgentUtils.supports.touch() === true) {
                // return false;
            }
            var $elements = this.__find('[data-component-name="SizePreview"] [data-size]', true);
            for (var $element of $elements) {
                var $img = $element.querySelector('img'),
                    $pane = $element.querySelector('div.vector'),
                    drift = new Drift($img, {
                        // handleTouch: false,
                        handleTouch: true,
                        containInline: true,
                        paneContainer: $pane,
                        hoverBoundingBox: true,
                        showWhitespaceAtEdges: true
                    });
            }
            return true;
        },

        /**
         * _showDownloadPopover
         * 
         * @access  protected
         * @return  Boolean
         */
        _showDownloadPopover: function() {
            this._downloadPopover.show();
            return true;
        }
    });
});
window.DependencyLoader.push(['BasePageView'], function() {

    /**
     * VectorSetPageView
     * 
     * @extends BasePageView
     */
    window.VectorSetPageView = BasePageView.extend({

        /**
         * Properties
         * 
         */

        /**
         * _string
         * 
         * @access  protected
         * @var     String (default: 'VectorSetPageView')
         */
        _string: 'VectorSetPageView',

        /**
         * _vectorSet
         * 
         * @access  protected
         * @var     null|VectorSetActiveRecord
         */
        _vectorSet: null,

        /**
         * Methods
         * 
         */

        /**
         * init
         * 
         * @access  public
         * @param   HTMLElement $element
         * @return  void
         */
        init: function($element) {
            this._super($element);
            this._setupVectorSet();
            this._addSearchClickEventListener();
        },

        /**
         * _addSearchClickEventListener
         * 
         * @access  protected
         * @return  Boolean
         */
        _addSearchClickEventListener: function() {
            var $anchor = this._$element.querySelector('[data-lookup="search"]');
            if ($anchor === null) {
                return false;
            }
            var handler = this._handleSearchClickEvent.bind(this);
            $anchor.addEventListener('click', function(event) {
                event.preventDefault();
                handler();
            });
            return true;
        },

        /**
         * _animateHeaderForm
         * 
         * @access  protected
         * @return  Boolean
         */
        _animateHeaderForm: function() {
            var header = FrameworkUtils.getComponentView('HeaderBlock');
            header.pulseForm();
            return true;
        },

        /**
         * _handleSearchClickEvent
         * 
         * @access  protected
         * @return  Boolean
         */
        _handleSearchClickEvent: function() {
            var selector = 'input[type="search"]',
                $input = this._$element.querySelector(selector),
                $anchor = this._$element.querySelector('[data-lookup="search"]'),
                vectorSetId = $anchor.getAttribute('data-vector-set-id'),
                text = 'vectorSetIds:' + (vectorSetId) + ' ';
            $input.value = text;
            $input.focus();
            this._animateHeaderForm();
            return true;
        },

        /**
         * _setupVectorSet
         * 
         * @access  protected
         * @return  Boolean
         */
        _setupVectorSet: function() {
            var publicData = window.__Iconduck.publicData.vectorSet,
                model = FrameworkUtils.getModel('VectorSet');
            this._vectorSet = model.setActiveRecord(publicData);
            return true;
        }
    });
});
