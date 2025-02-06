
/**
 * LoadUtils
 * 
 * This is a collection of methods that may be used during the load process,
 * as in they're required to be available before the <DOMContentLoaded> event
 * has fired.
 * 
 * @access  public
 * @var     Object
 */
window.LoadUtils = (function() {

    /**
     * Properties (private)
     * 
     */

    /**
     * __string
     * 
     * @access  private
     * @var     String (default: 'LoadUtils')
     */
    var __string = 'LoadUtils';

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
            window.__Iconduck = {};
            window.__Iconduck.config = {};
            window.__Iconduck.page = null;
            window.__Iconduck.publicData = {};
            return true;
        },

        /**
         * handleImageLoad
         * 
         * @access  public
         * @param   HTMLImageElement $img
         * @return  Boolean
         */
        handleImageLoad: function($img) {
            $img.classList.add('loaded');
            // $img.style['-webkit-mask-image'] = 'url(\'' + ($img.src) + '\')';
            // $img.removeAttribute('error');
            return true;
        },

        /**
         * handleImageLoadError
         * 
         * @access  public
         * @param   HTMLImageElement $img
         * @return  Boolean
         */
        handleImageLoadError: function($img) {
            var src = $img.getAttribute('src'),
                alternate = $img.getAttribute('data-alternate');
            $img.removeAttribute('onerror');
            $img.setAttribute('src', alternate);
            // $img.setAttribute('srcset', alternate);
            return true;
        },

        /**
         * setVectorThumbSizeClass
         * 
         * @access  public
         * @return  Boolean
         */
        setVectorThumbSizeClass: function() {
            document.body.classList.add('custom-vectorSizeSmall');
            if (document.cookie.match('vectorThumbPreviewSize%22:%22medium%22') !== null) {
                document.body.classList.remove('custom-vectorSizeSmall');
                document.body.classList.add('custom-vectorSizeMedium');
            }
            if (document.cookie.match('vectorThumbPreviewSize%22:%22large%22') !== null) {
                document.body.classList.remove('custom-vectorSizeSmall');
                document.body.classList.add('custom-vectorSizeLarge');
            }
            return true;
        },

        /**
         * updateVectorThumbPreviewFillColors
         * 
         * @todo    Use css "vars" instead
         * @access  public
         * @return  Boolean
         */
        updateVectorThumbPreviewFillColors: function() {
return false;
            var pattern = /vectorThumbPreviewFillColor%22:%22([^\)]*)/,
                matches = document.cookie.match(pattern);
            if (matches === null) {
                return false;
            }
            var color = matches[1] + ')',
                color = color.replace(/%2C/g, ','),
                color = color.replace(/%20/g, ' '),
                css = '',
                css = (css) + '[data-component-name="VectorBlock"].solid-1:not(.displayShowContrast-1) div.wrapper div.mask { background-color: ' + (color) + ';}',
                css = (css) + '[data-component-name="VectorBlock"].solid-1:not(.displayShowContrast-1) div.wrapper img.loaded { visibility: hidden; }',
                css = (css) + '[data-component-name="VectorBlock"].solid-1:not(.displayShowContrast-1) div.wrapper img.loaded + div.mask { opacity: 1.00; }',
                css = (css) + 'body[data-view="VectorPageView"] div.focus div.vector.solid-1:not(.displayShowContrast-1) div.wrapper div.mask { background-color: ' + (color) + ';}',
                css = (css) + 'body[data-view="VectorPageView"] div.focus div.vector.solid-1:not(.displayShowContrast-1) div.wrapper img.loaded { visibility: hidden; }',
                css = (css) + 'body[data-view="VectorPageView"] div.focus div.vector.solid-1:not(.displayShowContrast-1) div.wrapper img.loaded + div.mask { opacity: 1.00; }',
                css = (css) + '[data-component-name="PreviewModal"].solid-1:not(.displayShowContrast-1) div.wrapper div.mask { background-color: ' + (color) + ' !important;}',
                css = (css) + '[data-component-name="PreviewModal"].solid-1:not(.displayShowContrast-1) div.wrapper img.loaded { visibility: hidden !important; }',
                css = (css) + '[data-component-name="PreviewModal"].solid-1:not(.displayShowContrast-1) div.wrapper img.loaded + div.mask { opacity: 1.00 !important; }',
                $head = document.head || document.getElementsByTagName('head')[0],
                $style = document.createElement('style');
            $head.appendChild($style);
            $style.type = 'text/css';
            $style.appendChild(document.createTextNode(css));
            return true;
        }
    };
})();
LoadUtils.init();
