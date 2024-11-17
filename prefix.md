# Name prefices

<div class="Section1">

# GUI Elements

Below table specifies which prefixes to use when naming a GUI component.
It's very important to base the prefix from **what it
__looks like__ to the user**, not what actual
code was used to implement it\! E.g. a combo box can be implemented
either as a `<select>` or a `<datalist>` element, but it still looks
like a combo box so the prefix `cox` shall be used\!

<div class="table-wrap">

<table>
<thead>
<tr class="header">
<th><p><strong>Component Type</strong></p></th>
<th><p><strong>HTML<sup>1)</sup></strong></p></th>
<th><p><strong>Prefix</strong></p></th>
<th><p><strong>Example</strong></p></th>
<th><p><strong>Comments</strong></p></th>
<th><p><strong>Links</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Audio player</p></td>
<td><p><code>&lt;audio&gt;</code></p></td>
<td><p><code>aud</code></p></td>
<td><p><img src="https://tensrc.com/gui_naming/images/elex_audm.png" align="left" scrolling="no" width="159" id="elex_audm"/></p></td>
<td></td>
<td><p><a href="https://www.w3schools.com/tags/tag_audio.asp" class="external-link">https://www.w3schools.com/tags/tag_audio.asp</a></p></td>
</tr>
<tr class="even">
<td><p>Button</p></td>
<td><p><code>&lt;button&gt;</code><sup>3)</sup></p></td>
<td><p><code>btn</code></p></td>
<td><p><img src="https://tensrc.com/gui_naming/images/elex_btn.png" align="left" scrolling="auto" width="42" id="elex_btn"/></p></td>
<td></td>
<td><p><a href="https://www.w3schools.com/tags/tag_button.asp" class="external-link">https://www.w3schools.com/tags/tag_button.asp</a></p></td>
</tr>
<tr class="odd">
<td><p>Canvas</p></td>
<td><p><code>&lt;canvas&gt;</code></p></td>
<td><p><code>can</code></p></td>
<td><p> </p></td>
<td><p> </p></td>
<td><p><a href="https://www.w3schools.com/tags/tag_canvas.asp" class="external-link">https://www.w3schools.com/tags/tag_canvas.asp</a></p>
<p><a href="https://www.w3schools.com/tags/ref_canvas.asp" class="external-link">https://www.w3schools.com/tags/ref_canvas.asp</a></p></td>
</tr>
<tr class="even">
<td><p>Card</p></td>
<td><p><code>&lt;div&gt;</code></p></td>
<td><p><code>crd</code></p></td>
<td><img src="https://tensrc.com/gui_naming/images/elex_crd.png" align="left" scrolling="auto" width="125" id="elex_crd"></td>
<td><p>A presentation containing a mixed set of data, usually an image on top with data underneath. See also <code>swi</code>.</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p>Checkbox</p></td>
<td><p><code>&lt;input type="checkbox"&gt;</code></p></td>
<td><p><code>cbx</code></p></td>
<td><p><img src="https://tensrc.com/gui_naming/images/elex_cbx.png" align="left" scrolling="auto" width="180" id="elex_cbx"/></p></td>
<td></td>
<td><p> </p></td>
</tr>
<tr class="even">
<td><p>Combo box</p></td>
<td><p><code>&lt;datalist&gt;&lt;option&gt;</code></p></td>
<td><p><code>cox</code></p></td>
<td><img src="https://tensrc.com/gui_naming/images/elex_cox.png" align="left" scrolling="auto" width="203" id="elex_cox"/></td>
<td><p>Each element in the list shall have <code>sop</code> as prefix.</p>
<p>See also Selector option.</p></td>
<td><p><a href="https://www.w3schools.com/tags/tag_datalist.asp" class="external-link">https://www.w3schools.com/tags/tag_datalist.asp</a></p></td>
</tr>
<tr class="odd">
<td><p>Dialog box</p></td>
<td><p><code>&lt;dialog&gt;</code></p></td>
<td><p><code>dlg</code></p></td>
<td><img src="https://tensrc.com/gui_naming/images/elex_dlg.png" align="left" scrolling="auto" width="76" id="elex_dlg"/></td>
<td><p> </p></td>
<td><p><a href="https://www.w3schools.com/tags/tag_dialog.asp" class="external-link">https://www.w3schools.com/tags/tag_dialog.asp</a></p></td>
</tr>
<tr class="even">
<td><p>Div area<sup>2)</sup></p></td>
<td><p><code>&lt;div&gt;</code><sup>2)</sup></p></td>
<td><p><code>&lt;div&gt;</code><sup>2)</sup></p></td>
<td><img src="https://tensrc.com/gui_naming/images/elex_div.png" align="left" scrolling="auto" width="47" id="elex_div"/></td>
<td><p>Avoid if there are any more specific component types.</p></td>
<td><p> </p></td>
</tr>
<tr class="odd">
<td><p>Embedded element</p></td>
<td><p><code>&lt;embed&gt;</code></p></td>
<td><p><code>bed</code></p></td>
<td><p> </p></td>
<td><p> </p></td>
<td><p><a href="https://www.w3schools.com/tags/tag_embed.asp" class="external-link">https://www.w3schools.com/tags/tag_embed.asp</a></p></td>
</tr>
<tr class="even">
<td><p>Form<sup>4)</sup></p></td>
<td><p><code>&lt;form&gt;</code></p></td>
<td><p><code>for</code></p></td>
<td><p> </p></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
<tr class="odd">
<td><p>Frame</p></td>
<td><p><code>&lt;fieldset&gt;&lt;legend&gt;</code></p></td>
<td><p><code>frm</code></p></td>
<td><img src="https://tensrc.com/gui_naming/images/elex_frm.png" align="left" scrolling="auto" width="162" id="elex_frm"/></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
<tr class="even">
<td><p>General style (no component)</p></td>
<td><p> </p></td>
<td><p><code>sty</code></p></td>
<td><p> </p></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
<tr class="odd">
<td><p>Header</p></td>
<td><p><code>&lt;h1&gt;</code>, <code>&lt;h2&gt;</code>...</p></td>
<td><p><code>hdr</code></p></td>
<td><p><strong>My Profile</strong></p></td>
<td><p>Title of a page or section, which is not a label (<code>lbl</code>) nor ordinary text (<code>txt</code>).</p>
<p>Headers also serve as help for search engines (SEO).</p></td>
<td></td>
</tr>
<tr class="even">
<td><p>Hint</p></td>
<td><p> </p></td>
<td><p><code>hnt</code></p></td>
<td><img src="https://tensrc.com/gui_naming/images/elex_hnt.png" align="left" scrolling="auto" width="255" id="elex_hnt"/></td>
<td><p>A Hint is a tiny help text that pops up when user hovers the mouse over component (or on a mobile shows up during long press).</p></td>
<td><p> </p></td>
</tr>
<tr class="odd">
<td><p>Horizontal line</p></td>
<td><p> </p></td>
<td><p><code>hli</code></p></td>
<td><img src="https://tensrc.com/gui_naming/images/elex_hli.png" align="left" scrolling="auto" width="73" id="elex_hli"/></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
<tr class="even">
<td><p>Horizontal list</p></td>
<td><p> </p></td>
<td><p><code>hls</code></p></td>
<td><p> </p></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
<tr class="odd">
<td><p>Horizontal scroll bar</p></td>
<td><p><code>&lt;div style="overflow-x:scroll;&gt;</code></p></td>
<td><p><code>hsc</code></p></td>
<td><img src="https://tensrc.com/gui_naming/images/elex_hsc.png" align="left" scrolling="auto" width="67" id="elex_hsc"?></p></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
<tr class="even">
<td><p>Horizontal slider</p></td>
<td><p> </p></td>
<td><p><code>hsl</code></p></td>
<td><p> </p></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
<tr class="odd">
<td><p>Icon</p></td>
<td><p><code>&lt;img&gt;</code></p></td>
<td><p><code>ico</code></p></td>
<td><p> </p></td>
<td><p>A small image that can be pressed to make a selection. Note the <code>men</code> exception.</p></td>
<td><p> </p></td>
</tr>
<tr class="even">
<td><p>Iframe</p></td>
<td><p><code>&lt;iframe&gt;</code></p></td>
<td><p><code>ifr</code></p></td>
<td><p> </p></td>
<td><p> </p></td>
<td><p><a href="https://www.w3schools.com/tags/tag_iframe.asp" class="external-link">https://www.w3schools.com/tags/tag_iframe.asp</a></p></td>
</tr>
<tr class="odd">
<td><p>Image</p></td>
<td><p><code>&lt;img&gt;</code></p></td>
<td><p><code>img</code></p></td>
<td><p> </p></td>
<td><p>Also use the <code>img</code> prefix for images that are links to <code>svg</code> files (as in <code>&lt;img src="image.svg"&gt;</code>). If the image is drawn directly with <code>svg</code> commands inside an <code>&lt;svg&gt;</code> element, use <code>svg</code> prefix instead.</p></td>
<td><p> </p></td>
</tr>
<tr class="even">
<td><p>Image Map Area</p></td>
<td><p><code>&lt;area&gt;</code></p></td>
<td><p><code>ima</code></p></td>
<td><p> </p></td>
<td><p> </p></td>
<td><p><a href="https://www.w3schools.com/tags/tag_area.asp" class="external-link">https://www.w3schools.com/tags/tag_area.asp</a></p></td>
</tr>
<tr class="odd">
<td><p>Input field (single line)</p></td>
<td><p><code>&lt;input type="text"&gt;</code></p></td>
<td><p><code>inp</code></p></td>
<td><p> </p></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
<tr class="even">
<td><p>Irrelevant/obsolete</p></td>
<td><p> </p></td>
<td><p><code>nil</code></p></td>
<td><p> </p></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
<tr class="odd">
<td><p>Label (fixed text)</p></td>
<td><p><code>&lt;label&gt;</code></p></td>
<td><p><code>lbl</code></p></td>
<td><p> </p></td>
<td><p>Typically used in front of user input controls, table row or column names. Don't use it as headers (see <code>hdr</code>), nor flowing text (see <code>txt</code>).</p></td>
<td><p> </p></td>
</tr>
<tr class="even">
<td><p>Landing area</p></td>
<td><p><code>&lt;div&gt;</code></p></td>
<td><p><code>lnd</code></p></td>
<td><p> </p></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
<tr class="odd">
<td><p>Link</p></td>
<td><p><code>&lt;a href&gt;</code></p></td>
<td><p><code>lnk</code></p></td>
<td></td>
<td><p>Link</p></td>
<td></td>
</tr>
<tr class="even">
<td><p>List (any direction)</p></td>
<td><p><code>&lt;ul&gt;, &lt;ol&gt;</code></p></td>
<td><p><code>lst</code></p></td>
<td><img src="https://tensrc.com/gui_naming/images/elex_vls1.png" align="left" scrolling="auto" width="90" id="elex_vls1"/></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
<tr class="odd">
<td><p>List Item</p></td>
<td><p><code>&lt;li&gt;</code></p></td>
<td><p><code>lii</code></p></td>
<td><img src="https://tensrc.com/gui_naming/images/elex_vls2.png" align="left" scrolling="auto" width="96" id="elex_vls2"/></td>
<td><p> </p></td>
<td><p><a href="https://www.w3schools.com/tags/tag_li.asp" class="external-link">https://www.w3schools.com/tags/tag_li.asp</a></p></td>
</tr>
<tr class="even">
<td><p>Menu bar</p></td>
<td><p> </p></td>
<td><p><code>mbr</code></p></td>
<td><p> </p></td>
<td><p>Horizontal or vertical menu bar.</p></td>
<td><p> </p></td>
</tr>
<tr class="odd">
<td><p>Menu</p></td>
<td><p><code>&lt;img&gt;</code></p></td>
<td><p><code>men</code></p></td>
<td><p> </p></td>
<td><p>The control that opens a menu. Typically three dots, nine squares or three horizontal lines. Use <code>men</code> instead of <code>img</code> and <code>ico</code> even if the control is represented by an image or icon.</p></td>
<td><p> </p></td>
</tr>
<tr class="even">
<td><p>Menu option</p></td>
<td><p> </p></td>
<td><p><code>mop</code></p></td>
<td><p> </p></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
<tr class="odd">
<td><p>Page</p></td>
<td><p><code>&lt;html&gt;&lt;page&gt;</code></p></td>
<td><p><code>pag</code></p></td>
<td><p> </p></td>
<td><p>Every separate web or mobile app page must have the <code>pag</code> prefix.</p></td>
<td><p> </p></td>
</tr>
<tr class="even">
<td><p>Panel</p></td>
<td><p><code>&lt;div&gt;</code></p></td>
<td><p><code>pan</code></p></td>
<td><p> </p></td>
<td><p>On a web page, a panel is usually a section on the left or right side of the main page. On mobiles they are usually shown as overlays when users swipe a page or presses a strap. See also <code>stp</code>.</p></td>
<td><p> </p></td>
</tr>
<tr class="odd">
<td><p>Progress bar</p></td>
<td><p><code>&lt;progress&gt;</code></p></td>
<td><p><code>pbr</code></p></td>
<td><p> </p></td>
<td><p> </p></td>
<td><p><a href="https://www.w3schools.com/howto/howto_js_progressbar.asp" class="external-link">https://www.w3schools.com/howto/howto_js_progressbar.asp</a></p>
<p><a href="https://www.w3schools.com/tags/tag_progress.asp" class="external-link">https://www.w3schools.com/tags/tag_progress.asp</a></p></td>
</tr>
<tr class="even">
<td><p>Prompt</p></td>
<td></td>
<td><p><code>prm</code></p></td>
<td></td>
<td><p>Text shown in an input field telling what is expected.</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p>Radio button</p></td>
<td><p><code>&lt;input type="radio"&gt;</code></p></td>
<td><p><code>rad</code></p></td>
<td><img src="https://tensrc.com/gui_naming/images/elex_rad.png" align="left" scrolling="auto" width="175" id="elex_rad"/></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
<tr class="even">
<td><p>Selector</p></td>
<td><p><code>&lt;select&gt;</code></p></td>
<td><p><code>sel</code></p></td>
<td><p> </p></td>
<td><p>See also Combo box.</p></td>
<td><p> </p></td>
</tr>
<tr class="odd">
<td><p>Selector option</p></td>
<td><p><code>&lt;option&gt;</code></p></td>
<td><p><code>sop</code></p></td>
<td><img src="https://tensrc.com/gui_naming/images/elex_sop.png" align="left" scrolling="auto" width="61"/></td>
<td><p>See also Combo box.</p></td>
<td><p> </p></td>
</tr>
<tr class="even">
<td><p>Slider (any direction)</p></td>
<td><p> </p></td>
<td><p><code>sld</code></p></td>
<td><p> </p></td>
<td><p>Use the same prefix also for Range Sliders.</p></td>
<td><p> </p></td>
</tr>
<tr class="odd">
<td><p>Status bar</p></td>
<td><p> </p></td>
<td><p><code>sta</code></p></td>
<td><p> </p></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
<tr class="even">
<td><p>Strap</p></td>
<td><p> </p></td>
<td><p><code>stp</code></p></td>
<td><p> </p></td>
<td><p>A strap is a small text box at the side of the page which, when pressed, pulls out a panel. They are typically used on mobiles to pull out rating, contact and help panels. See also <code>pan</code>.</p></td>
<td><p> </p></td>
</tr>
<tr class="odd">
<td><p>SVG container</p></td>
<td><p><code>&lt;svg&gt;</code></p></td>
<td><p><code>svg</code></p></td>
<td><p> </p></td>
<td><p>Only use this for real HTML <code>&lt;svg&gt;</code> elements that directly contain svg code. For links to images containing svg code, use <code>img</code>.</p></td>
<td><p><a href="https://www.w3schools.com/tags/tag_svg.asp" class="external-link">https://www.w3schools.com/tags/tag_svg.asp</a></p></td>
</tr>
<tr class="even">
<td><p>Swipe</p></td>
<td></td>
<td><p><code>swi</code></p></td>
<td></td>
<td><p>This is a control that reacts proportionally to the swiping of a finger over the control. Can be used to browse through a set of images etc.</p>
<p>A.k.a Carousel. See also <code>crd</code>.</p></td>
<td><p><a href="https://dev.to/ayushmanbthakur/mobile-first-design-with-swipe-controls-in-website-2n6p" class="external-link">https://dev.to/ayushmanbthakur/mobile-first-design-with-swipe-controls-in-website-2n6p</a></p></td>
</tr>
<tr class="odd">
<td><p>Tab</p></td>
<td><p> </p></td>
<td><p><code>tab</code></p></td>
<td><p> </p></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
<tr class="even">
<td><p>Table</p></td>
<td><p><code>&lt;table&gt;</code></p></td>
<td><p><code>tbl</code></p></td>
<td><img src="https://tensrc.com/gui_naming/images/elex_tbl.png" align="left" scrolling="auto" width="37" id="elex_tbl"/></td>
<td><p> </p></td>
<td><p><a href="https://www.w3schools.com/tags/tag_table.asp" class="external-link">https://www.w3schools.com/tags/tag_table.asp</a></p></td>
</tr>
<tr class="odd">
<td><p>Table body</p></td>
<td><p><code>&lt;tbody&gt;</code></p></td>
<td><p><code>tbo</code></p></td>
<td><p> </p></td>
<td><p> </p></td>
<td><p><a href="https://www.w3schools.com/tags/tag_tbody.asp" class="external-link">https://www.w3schools.com/tags/tag_tbody.asp</a></p></td>
</tr>
<tr class="even">
<td><p>Table caption</p></td>
<td><p><code>&lt;caption&gt;</code></p></td>
<td><p><code>tca</code></p></td>
<td><p> </p></td>
<td><p> </p></td>
<td><p><a href="https://www.w3schools.com/tags/tag_caption.asp" class="external-link">https://www.w3schools.com/tags/tag_caption.asp</a></p></td>
</tr>
<tr class="odd">
<td><p>Table data</p></td>
<td><p><code>&lt;td&gt;</code></p></td>
<td><p><code>ttd</code></p></td>
<td><p> </p></td>
<td><p> </p></td>
<td><p><a href="https://www.w3schools.com/tags/tag_td.asp" class="external-link">https://www.w3schools.com/tags/tag_td.asp</a></p></td>
</tr>
<tr class="even">
<td><p>Table foot</p></td>
<td><p><code>&lt;tfoot&gt;</code></p></td>
<td><p><code>tfo</code></p></td>
<td><p> </p></td>
<td><p> </p></td>
<td><p><a href="https://www.w3schools.com/tags/tag_tfoot.asp" class="external-link">https://www.w3schools.com/tags/tag_tfoot.asp</a></p></td>
</tr>
<tr class="odd">
<td><p>Table head</p></td>
<td><p><code>&lt;thead&gt;</code></p></td>
<td><p><code>the</code></p></td>
<td><p> </p></td>
<td><p> </p></td>
<td><p><a href="https://www.w3schools.com/tags/tag_th.asp" class="external-link">https://www.w3schools.com/tags/tag_th.asp</a></p></td>
</tr>
<tr class="even">
<td><p>Table row</p></td>
<td><p><code>&lt;tr&gt;</code></p></td>
<td><p><code>ttr</code></p></td>
<td><p> </p></td>
<td><p> </p></td>
<td><p><a href="https://www.w3schools.com/tags/tag_tr.asp" class="external-link">https://www.w3schools.com/tags/tag_tr.asp</a></p></td>
</tr>
<tr class="odd">
<td><p>Text</p></td>
<td><p><code>&lt;p&gt;</code></p></td>
<td><p><code>txt</code></p></td>
<td><p>This is just some instructive text.</p></td>
<td><p>Text not related to any input control, not editable by the user. See also <code>lbl</code>, <code>var</code> and <code>hdr</code>.</p>
<p>The <code>txt</code> prefix shall be used for the text only, disregarding alignment, font, text size and other attributes. To define those, put the <code>txt</code> element inside a Text Style Attribute (<code>tsa</code>).</p></td>
<td><p><a href="https://www.w3schools.com/tags/tag_p.asp" class="external-link">https://www.w3schools.com/tags/tag_p.asp</a></p></td>
</tr>
<tr class="even">
<td><p>Text area (multi-line)</p></td>
<td><p><code>&lt;textarea&gt;</code></p></td>
<td><p><code>are</code></p></td>
<td><img src="https://tensrc.com/gui_naming/images/elex_are.png" align="left" scrolling="auto" width="80" id="elex_are"/></td>
<td><p> This is a box where the user can enter multiple lines of text.</p></td>
<td><p> </p></td>
</tr>
<tr class="odd">
<td><p>Text Style Attribute</p></td>
<td><p><code>&lt;div&gt;</code></p></td>
<td><p><code>tsa</code></p></td>
<td></td>
<td><p>This is a pseudo element specifying styles for text (<code>txt</code>) inside it.</p></td>
<td></td>
</tr>
<tr class="even">
<td><p>Variable text value</p></td>
<td><p><code>&lt;var&gt;</code></p></td>
<td><p><code>var</code></p></td>
<td><img src="https://tensrc.com/gui_naming/images/elex_var.png" align="left" scrolling="auto" width="233" id="elex_var"/><p>Assume the user has selected Euro as preferred currency, so the <code>EUR</code> part of above label could be a component prefixed with <code>var</code>.</p></td>
<td><p>A variable text value is a pre-defined alternative text that isn't editable by the user but may vary depending on user's preferences or earlier user input. They are usually a variable part of a label or table cell values.</p></td>
<td><p> </p></td>
</tr>
<tr class="odd">
<td><p>Vertical line</p></td>
<td><p> </p></td>
<td><p><code>vli</code></p></td>
<td><img src="https://tensrc.com/gui_naming/images/elex_vli.png" align="left" scrolling="auto" width="20" id="elex_vli"/></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
<tr class="even">
<td><p>Vertical list</p></td>
<td><p><code>&lt;ul&gt;, &lt;ol&gt;</code></p></td>
<td><p><code>vls</code></p></td>
<td></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
<tr class="odd">
<td><p>Vertical scroll bar</p></td>
<td><p> </p></td>
<td><p><code>vsc</code></p></td>
<td><img src="https://tensrc.com/gui_naming/images/elex_vsc.png" align="left" scrolling="auto" width="22" id="elex_vsc"/></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
<tr class="even">
<td><p>Vertical slider</p></td>
<td><p> </p></td>
<td><p><code>vsl</code></p></td>
<td><p> </p></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
</tbody>
</table>

</div>

## Footnotes

1.  The **HTML** column shall be seen as an example of a possible way to
    create the corresponding component only. Most components can be
    created using more than one type of HTML code.

2.  The `div` prefix must be avoided as it is too neutral. Try to find a
    more distinct name prefix even if you use a `<div>` element to
    implement it.

3.  Although buttons can be implemented with HTML elements `<input>` and
    `<div>` as well, using `<button>` is preferred, and the component's
    name prefix shall always be `btn`\!

4.  A form can look like anything and may not have distinct visibility.
    But we still need to give it a name as a way to indicate which child
    components belongs to it.

# GUI Attributes

<div class="table-wrap">

<table>
<thead>
<tr class="header">
<th><p><strong>Style Type</strong></p></th>
<th><p><strong>CSS</strong></p></th>
<th><p><strong>Prefix</strong></p></th>
<th><p><strong>Postfix</strong></p></th>
<th><p><strong>Example</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Background Color</p></td>
<td><p><code>background-color</code></p></td>
<td><p><code>col</code></p></td>
<td><p><code>BG</code></p></td>
<td><img src="https://tensrc.com/gui_naming/images/atex_bg.png" align="left" scrolling="auto" width="56" id="atex_bg"/><br />
<br />
<code>colInfoBG</code></td>
</tr>
<tr class="even">
<td><p>Foreground Color</p></td>
<td><p><code>color</code></p></td>
<td><p><code>col</code></p></td>
<td><p><code>FG</code></p></td>
<td><img src="https://tensrc.com/gui_naming/images/atex_fg.png" align="left" scrolling="auto" width="62" id="atex_fg"/><br />
<br />
<code>colWarningFG</code></td>
</tr>
<tr class="odd">
<td><p>Text Style</p></td>
<td><p><code>font-style</code>, <code>font-size</code>...</p></td>
<td><p><code>sty</code></p></td>
<td><p> </p></td>
<td><p><strong>TITLE</strong><br />
<br />
styPageTitle</p></td>
</tr>
</tbody>
</table>

</div>

# Hierarchical Names and div Objects

Sometimes an object contains other objects, but it doesn't feel logical
to invent new names for each of them. In this case we can just add more
prefixes, starting with the outermost component type.

Example: Suppose we want to create a Figma frame around a vector drawing
to position it equally relative to others in the same context. If e.g.
the drawing (a vector graphic) is named `drwMail`, the surrounding frame
can be called `divDrwMail`. This is not encourage though. If we could
instead call it `divMail`, it's better.

# Pseudo Elements

From time to time we need to draw elements which shall not be included
in production. This can be leading texts and backgrounds in Figma or
examples. We call these Pseudo Elements. They shall be identified by a
leading underscore (`_`). Example: `_pagLogin`, `_btnExample`.

Grids are also a form of pseudo elements but are not named with leading
underscore, just prefixed `grd`. They are instantiated by style
attributes in source code and HTML.

Text Style Attributes (`tsa`) can also be considered being pseudo
elements, but don't begin with underscore. They are used to specify the
style of the text element (`txt`) inside it. A `tsa` element must have a
class specified to it, which specifies the text styles via corresponding
CSS file.

# Referencing Objects in Text

To reference a specific object in a Figma design (when we talk about it
via email, Slack etc. or refer to it in a specification), the page name
must appear first (e.g. `pagLogin`). Unless we just want to refer to the
page itself, the object shall then follow either after a dot (e.g.
`pagLogin.secControls`), with intermediate elements listed between (e.g.
`pagLogin.secControls.btnSubmit`) or with intermediate irrelevant
objects omitted and replaced by ellipses (e.g. `pagLogin...btnSubmit`).

# Naming Limitations

Figma doesn't appear to declare any limits and restrictions to component
names, but we need it internally, thus we set the following rules:

1.  No component or object name may have a total length longer than 128
    characters (for variants, the total path is limited to this length).

2.  Only ASCII characters (A-Z, a-z, \_, /, 0-9) may be used.

</div>
