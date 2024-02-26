# CryptoClustering

CryptoClustering Overview

# Introduction
Utilize Python and unsupervised learning to predict the impact of 24-hour or 7-day price changes on cryptocurrencies.


# Data Sources
Located within the Resources Folder:

crypto_market_data.csv


# Key Findings
Elbow Curve Analysis:
Elbow Curve

<div id='p1170'>
  <div id="e7a3b9b2-c087-4d58-8d92-4f512b00ed47" data-root-id="p1170" style="display: contents;"></div>
</div>
<script type="application/javascript">(function(root) {
  var docs_json = {"42819af1-980b-4f61-92d6-53a4d90c5879":{"version":"3.2.1","title":"Bokeh Application","roots":[{"type":"object","name":"Row","id":"p1170","attributes":{"name":"Row01345","tags":["embedded"],"stylesheets":["\n:host(.pn-loading.pn-arc):before, .pn-loading.pn-arc:before {\n  background-image: url(\"data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHN0eWxlPSJtYXJnaW46IGF1dG87IGJhY2tncm91bmQ6IG5vbmU7IGRpc3BsYXk6IGJsb2NrOyBzaGFwZS1yZW5kZXJpbmc6IGF1dG87IiB2aWV3Qm94PSIwIDAgMTAwIDEwMCIgcHJlc2VydmVBc3BlY3RSYXRpbz0ieE1pZFlNaWQiPiAgPGNpcmNsZSBjeD0iNTAiIGN5PSI1MCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjYzNjM2MzIiBzdHJva2Utd2lkdGg9IjEwIiByPSIzNSIgc3Ryb2tlLWRhc2hhcnJheT0iMTY0LjkzMzYxNDMxMzQ2NDE1IDU2Ljk3Nzg3MTQzNzgyMTM4Ij4gICAgPGFuaW1hdGVUcmFuc2Zvcm0gYXR0cmlidXRlTmFtZT0idHJhbnNmb3JtIiB0eXBlPSJyb3RhdGUiIHJlcGVhdENvdW50PSJpbmRlZmluaXRlIiBkdXI9IjFzIiB2YWx1ZXM9IjAgNTAgNTA7MzYwIDUwIDUwIiBrZXlUaW1lcz0iMDsxIj48L2FuaW1hdGVUcmFuc2Zvcm0+ICA8L2NpcmNsZT48L3N2Zz4=\");\n  background-size: auto calc(min(50%, 400px));\n}",{"type":"object","name":"ImportedStyleSheet","id":"p1173","attributes":{"url":"https://cdn.holoviz.org/panel/1.2.3/dist/css/loading.css"}},{"type":"object","name":"ImportedStyleSheet","id":"p1226","attributes":{"url":"https://cdn.holoviz.org/panel/1.2.3/dist/css/listpanel.css"}},{"type":"object","name":"ImportedStyleSheet","id":"p1171","attributes":{"url":"https://cdn.holoviz.org/panel/1.2.3/dist/bundled/theme/default.css"}},{"type":"object","name":"ImportedStyleSheet","id":"p1172","attributes":{"url":"https://cdn.holoviz.org/panel/1.2.3/dist/bundled/theme/native.css"}}],"min_width":700,"margin":0,"sizing_mode":"stretch_width","align":"start","children":[{"type":"object","name":"Spacer","id":"p1174","attributes":{"name":"HSpacer01356","stylesheets":["\n:host(.pn-loading.pn-arc):before, .pn-loading.pn-arc:before {\n  background-image: url(\"data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHN0eWxlPSJtYXJnaW46IGF1dG87IGJhY2tncm91bmQ6IG5vbmU7IGRpc3BsYXk6IGJsb2NrOyBzaGFwZS1yZW5kZXJpbmc6IGF1dG87IiB2aWV3Qm94PSIwIDAgMTAwIDEwMCIgcHJlc2VydmVBc3BlY3RSYXRpbz0ieE1pZFlNaWQiPiAgPGNpcmNsZSBjeD0iNTAiIGN5PSI1MCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjYzNjM2MzIiBzdHJva2Utd2lkdGg9IjEwIiByPSIzNSIgc3Ryb2tlLWRhc2hhcnJheT0iMTY0LjkzMzYxNDMxMzQ2NDE1IDU2Ljk3Nzg3MTQzNzgyMTM4Ij4gICAgPGFuaW1hdGVUcmFuc2Zvcm0gYXR0cmlidXRlTmFtZT0idHJhbnNmb3JtIiB0eXBlPSJyb3RhdGUiIHJlcGVhdENvdW50PSJpbmRlZmluaXRlIiBkdXI9IjFzIiB2YWx1ZXM9IjAgNTAgNTA7MzYwIDUwIDUwIiBrZXlUaW1lcz0iMDsxIj48L2FuaW1hdGVUcmFuc2Zvcm0+ICA8L2NpcmNsZT48L3N2Zz4=\");\n  background-size: auto calc(min(50%, 400px));\n}",{"id":"p1173"},{"id":"p1171"},{"id":"p1172"}],"margin":0,"sizing_mode":"stretch_width","align":"start"}},{"type":"object","name":"Figure","id":"p1182","attributes":{"width":700,"height":300,"margin":[5,10],"sizing_mode":"fixed","align":"start","x_range":{"type":"object","name":"Range1d","id":"p1175","attributes":{"tags":[[["k","k",null]],[]],"start":1.0,"end":11.0,"reset_start":1.0,"reset_end":11.0}},"y_range":{"type":"object","name":"Range1d","id":"p1176","attributes":{"tags":[[["inertia","inertia",null]],{"type":"map","entries":[["invert_yaxis",false],["autorange",false]]}],"start":-2.4209512090842544,"end":313.3109955644622,"reset_start":-2.4209512090842544,"reset_end":313.3109955644622}},"x_scale":{"type":"object","name":"LinearScale","id":"p1192"},"y_scale":{"type":"object","name":"LinearScale","id":"p1193"},"title":{"type":"object","name":"Title","id":"p1185","attributes":{"text":"Elbow Curve","text_color":"black","text_font_size":"12pt"}},"renderers":[{"type":"object","name":"GlyphRenderer","id":"p1218","attributes":{"data_source":{"type":"object","name":"ColumnDataSource","id":"p1209","attributes":{"selected":{"type":"object","name":"Selection","id":"p1210","attributes":{"indices":[],"line_indices":[]}},"selection_policy":{"type":"object","name":"UnionRenderers","id":"p1211"},"data":{"type":"map","entries":[["k",{"type":"ndarray","array":{"type":"bytes","data":"AQAAAAIAAAADAAAABAAAAAUAAAAGAAAABwAAAAgAAAAJAAAACgAAAAsAAAA="},"shape":[11],"dtype":"int32","order":"little"}],["inertia",{"type":"ndarray","array":{"type":"bytes","data":"AAAAAADwcUDmwndVTNJoQOCRvNowzF5AF+6ulG/BU0BnEQsuWlNQQOdykvoHDUpAmOLlEoMER0DEjt+KdKRCQIIPyVCpFEBAFoNuwkMTPEB0Vmby2eM3QA=="},"shape":[11],"dtype":"float64","order":"little"}]]}}},"view":{"type":"object","name":"CDSView","id":"p1219","attributes":{"filter":{"type":"object","name":"AllIndices","id":"p1220"}}},"glyph":{"type":"object","name":"Line","id":"p1215","attributes":{"tags":["apply_ranges"],"x":{"type":"field","field":"k"},"y":{"type":"field","field":"inertia"},"line_color":"#30a2da","line_width":2}},"selection_glyph":{"type":"object","name":"Line","id":"p1221","attributes":{"tags":["apply_ranges"],"x":{"type":"field","field":"k"},"y":{"type":"field","field":"inertia"},"line_color":"#30a2da","line_width":2}},"nonselection_glyph":{"type":"object","name":"Line","id":"p1216","attributes":{"tags":["apply_ranges"],"x":{"type":"field","field":"k"},"y":{"type":"field","field":"inertia"},"line_color":"#30a2da","line_alpha":0.1,"line_width":2}},"muted_glyph":{"type":"object","name":"Line","id":"p1217","attributes":{"tags":["apply_ranges"],"x":{"type":"field","field":"k"},"y":{"type":"field","field":"inertia"},"line_color":"#30a2da","line_alpha":0.2,"line_width":2}}}}],"toolbar":{"type":"object","name":"Toolbar","id":"p1191","attributes":{"tools":[{"type":"object","name":"WheelZoomTool","id":"p1180","attributes":{"tags":["hv_created"],"zoom_together":"none"}},{"type":"object","name":"HoverTool","id":"p1181","attributes":{"tags":["hv_created"],"renderers":[{"id":"p1218"}],"tooltips":[["k","@{k}"],["inertia","@{inertia}"]]}},{"type":"object","name":"SaveTool","id":"p1204"},{"type":"object","name":"PanTool","id":"p1205"},{"type":"object","name":"BoxZoomTool","id":"p1206","attributes":{"overlay":{"type":"object","name":"BoxAnnotation","id":"p1207","attributes":{"syncable":false,"level":"overlay","visible":false,"left_units":"canvas","right_units":"canvas","bottom_units":"canvas","top_units":"canvas","line_color":"black","line_alpha":1.0,"line_width":2,"line_dash":[4,4],"fill_color":"lightgrey","fill_alpha":0.5}}}},{"type":"object","name":"ResetTool","id":"p1208"}],"active_drag":{"id":"p1205"},"active_scroll":{"id":"p1180"}}},"left":[{"type":"object","name":"LinearAxis","id":"p1199","attributes":{"ticker":{"type":"object","name":"BasicTicker","id":"p1200","attributes":{"mantissas":[1,2,5]}},"formatter":{"type":"object","name":"BasicTickFormatter","id":"p1201"},"axis_label":"inertia","major_label_policy":{"type":"object","name":"AllLabels","id":"p1202"}}}],"below":[{"type":"object","name":"LinearAxis","id":"p1194","attributes":{"ticker":{"type":"object","name":"FixedTicker","id":"p1222","attributes":{"ticks":[1,2,3,4,5,6,7,8,9,10,11],"minor_ticks":[]}},"formatter":{"type":"object","name":"BasicTickFormatter","id":"p1196"},"axis_label":"k","major_label_policy":{"type":"object","name":"AllLabels","id":"p1197"}}}],"center":[{"type":"object","name":"Grid","id":"p1198","attributes":{"axis":{"id":"p1194"},"grid_line_color":null}},{"type":"object","name":"Grid","id":"p1203","attributes":{"dimension":1,"axis":{"id":"p1199"},"grid_line_color":null}}],"min_border_top":10,"min_border_bottom":10,"min_border_left":10,"min_border_right":10,"output_backend":"webgl"}},{"type":"object","name":"Spacer","id":"p1224","attributes":{"name":"HSpacer01359","stylesheets":["\n:host(.pn-loading.pn-arc):before, .pn-loading.pn-arc:before {\n  background-image: url(\"data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHN0eWxlPSJtYXJnaW46IGF1dG87IGJhY2tncm91bmQ6IG5vbmU7IGRpc3BsYXk6IGJsb2NrOyBzaGFwZS1yZW5kZXJpbmc6IGF1dG87IiB2aWV3Qm94PSIwIDAgMTAwIDEwMCIgcHJlc2VydmVBc3BlY3RSYXRpbz0ieE1pZFlNaWQiPiAgPGNpcmNsZSBjeD0iNTAiIGN5PSI1MCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjYzNjM2MzIiBzdHJva2Utd2lkdGg9IjEwIiByPSIzNSIgc3Ryb2tlLWRhc2hhcnJheT0iMTY0LjkzMzYxNDMxMzQ2NDE1IDU2Ljk3Nzg3MTQzNzgyMTM4Ij4gICAgPGFuaW1hdGVUcmFuc2Zvcm0gYXR0cmlidXRlTmFtZT0idHJhbnNmb3JtIiB0eXBlPSJyb3RhdGUiIHJlcGVhdENvdW50PSJpbmRlZmluaXRlIiBkdXI9IjFzIiB2YWx1ZXM9IjAgNTAgNTA7MzYwIDUwIDUwIiBrZXlUaW1lcz0iMDsxIj48L2FuaW1hdGVUcmFuc2Zvcm0+ICA8L2NpcmNsZT48L3N2Zz4=\");\n  background-size: auto calc(min(50%, 400px));\n}",{"id":"p1173"},{"id":"p1171"},{"id":"p1172"}],"margin":0,"sizing_mode":"stretch_width","align":"start"}}]}}],"defs":[{"type":"model","name":"ReactiveHTML1"},{"type":"model","name":"FlexBox1","properties":[{"name":"align_content","kind":"Any","default":"flex-start"},{"name":"align_items","kind":"Any","default":"flex-start"},{"name":"flex_direction","kind":"Any","default":"row"},{"name":"flex_wrap","kind":"Any","default":"wrap"},{"name":"justify_content","kind":"Any","default":"flex-start"}]},{"type":"model","name":"FloatPanel1","properties":[{"name":"config","kind":"Any","default":{"type":"map"}},{"name":"contained","kind":"Any","default":true},{"name":"position","kind":"Any","default":"right-top"},{"name":"offsetx","kind":"Any","default":null},{"name":"offsety","kind":"Any","default":null},{"name":"theme","kind":"Any","default":"primary"},{"name":"status","kind":"Any","default":"normalized"}]},{"type":"model","name":"GridStack1","properties":[{"name":"mode","kind":"Any","default":"warn"},{"name":"ncols","kind":"Any","default":null},{"name":"nrows","kind":"Any","default":null},{"name":"allow_resize","kind":"Any","default":true},{"name":"allow_drag","kind":"Any","default":true},{"name":"state","kind":"Any","default":[]}]},{"type":"model","name":"drag1","properties":[{"name":"slider_width","kind":"Any","default":5},{"name":"slider_color","kind":"Any","default":"black"},{"name":"value","kind":"Any","default":50}]},{"type":"model","name":"click1","properties":[{"name":"terminal_output","kind":"Any","default":""},{"name":"debug_name","kind":"Any","default":""},{"name":"clears","kind":"Any","default":0}]},{"type":"model","name":"FastWrapper1","properties":[{"name":"object","kind":"Any","default":null},{"name":"style","kind":"Any","default":null}]},{"type":"model","name":"NotificationAreaBase1","properties":[{"name":"js_events","kind":"Any","default":{"type":"map"}},{"name":"position","kind":"Any","default":"bottom-right"},{"name":"_clear","kind":"Any","default":0}]},{"type":"model","name":"NotificationArea1","properties":[{"name":"js_events","kind":"Any","default":{"type":"map"}},{"name":"notifications","kind":"Any","default":[]},{"name":"position","kind":"Any","default":"bottom-right"},{"name":"_clear","kind":"Any","default":0},{"name":"types","kind":"Any","default":[{"type":"map","entries":[["type","warning"],["background","#ffc107"],["icon",{"type":"map","entries":[["className","fas fa-exclamation-triangle"],["tagName","i"],["color","white"]]}]]},{"type":"map","entries":[["type","info"],["background","#007bff"],["icon",{"type":"map","entries":[["className","fas fa-info-circle"],["tagName","i"],["color","white"]]}]]}]}]},{"type":"model","name":"Notification","properties":[{"name":"background","kind":"Any","default":null},{"name":"duration","kind":"Any","default":3000},{"name":"icon","kind":"Any","default":null},{"name":"message","kind":"Any","default":""},{"name":"notification_type","kind":"Any","default":null},{"name":"_destroyed","kind":"Any","default":false}]},{"type":"model","name":"TemplateActions1","properties":[{"name":"open_modal","kind":"Any","default":0},{"name":"close_modal","kind":"Any","default":0}]},{"type":"model","name":"BootstrapTemplateActions1","properties":[{"name":"open_modal","kind":"Any","default":0},{"name":"close_modal","kind":"Any","default":0}]},{"type":"model","name":"MaterialTemplateActions1","properties":[{"name":"open_modal","kind":"Any","default":0},{"name":"close_modal","kind":"Any","default":0}]}]}};
  var render_items = [{"docid":"42819af1-980b-4f61-92d6-53a4d90c5879","roots":{"p1170":"e7a3b9b2-c087-4d58-8d92-4f512b00ed47"},"root_ids":["p1170"]}];
  var docs = Object.values(docs_json)
  if (!docs) {
    return
  }
  const py_version = docs[0].version.replace('rc', '-rc.').replace('.dev', '-dev.')
  const is_dev = py_version.indexOf("+") !== -1 || py_version.indexOf("-") !== -1
  function embed_document(root) {
    var Bokeh = get_bokeh(root)
    Bokeh.embed.embed_items_notebook(docs_json, render_items);
    for (const render_item of render_items) {
      for (const root_id of render_item.root_ids) {
	const id_el = document.getElementById(root_id)
	if (id_el.children.length && (id_el.children[0].className === 'bk-root')) {
	  const root_el = id_el.children[0]
	  root_el.id = root_el.id + '-rendered'
	}
      }
    }
  }
  function get_bokeh(root) {
    if (root.Bokeh === undefined) {
      return null
    } else if (root.Bokeh.version !== py_version && !is_dev) {
      if (root.Bokeh.versions === undefined || !root.Bokeh.versions.has(py_version)) {
	return null
      }
      return root.Bokeh.versions.get(py_version);
    } else if (root.Bokeh.version === py_version) {
      return root.Bokeh
    }
    return null
  }
  function is_loaded(root) {
    var Bokeh = get_bokeh(root)
    return (Bokeh != null && Bokeh.Panel !== undefined)
  }
  if (is_loaded(root)) {
    embed_document(root);
  } else {
    var attempts = 0;
    var timer = setInterval(function(root) {
      if (is_loaded(root)) {
        clearInterval(timer);
        embed_document(root);
      } else if (document.readyState == "complete") {
        attempts++;
        if (attempts > 200) {
          clearInterval(timer);
	  var Bokeh = get_bokeh(root)
	  if (Bokeh == null || Bokeh.Panel == null) {
            console.warn("Panel: ERROR: Unable to run Panel code because Bokeh or Panel library is missing");
	  } else {
	    console.warn("Panel: WARNING: Attempting to render but not all required libraries could be resolved.")
	    embed_document(root)
	  }
        }
      }
    }, 25, root)
  }
})(window);</script>

Elbow Curve for PCA Data
<div id='p1348'>
  <div id="dcfade00-8e5c-4a3d-837b-bce921abb21a" data-root-id="p1348" style="display: contents;"></div>
</div>
<script type="application/javascript">(function(root) {
  var docs_json = {"9d7f11e4-e358-4b0d-98bf-e03642e8de44":{"version":"3.2.1","title":"Bokeh Application","roots":[{"type":"object","name":"Row","id":"p1348","attributes":{"name":"Row01735","tags":["embedded"],"stylesheets":["\n:host(.pn-loading.pn-arc):before, .pn-loading.pn-arc:before {\n  background-image: url(\"data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHN0eWxlPSJtYXJnaW46IGF1dG87IGJhY2tncm91bmQ6IG5vbmU7IGRpc3BsYXk6IGJsb2NrOyBzaGFwZS1yZW5kZXJpbmc6IGF1dG87IiB2aWV3Qm94PSIwIDAgMTAwIDEwMCIgcHJlc2VydmVBc3BlY3RSYXRpbz0ieE1pZFlNaWQiPiAgPGNpcmNsZSBjeD0iNTAiIGN5PSI1MCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjYzNjM2MzIiBzdHJva2Utd2lkdGg9IjEwIiByPSIzNSIgc3Ryb2tlLWRhc2hhcnJheT0iMTY0LjkzMzYxNDMxMzQ2NDE1IDU2Ljk3Nzg3MTQzNzgyMTM4Ij4gICAgPGFuaW1hdGVUcmFuc2Zvcm0gYXR0cmlidXRlTmFtZT0idHJhbnNmb3JtIiB0eXBlPSJyb3RhdGUiIHJlcGVhdENvdW50PSJpbmRlZmluaXRlIiBkdXI9IjFzIiB2YWx1ZXM9IjAgNTAgNTA7MzYwIDUwIDUwIiBrZXlUaW1lcz0iMDsxIj48L2FuaW1hdGVUcmFuc2Zvcm0+ICA8L2NpcmNsZT48L3N2Zz4=\");\n  background-size: auto calc(min(50%, 400px));\n}",{"type":"object","name":"ImportedStyleSheet","id":"p1351","attributes":{"url":"https://cdn.holoviz.org/panel/1.2.3/dist/css/loading.css"}},{"type":"object","name":"ImportedStyleSheet","id":"p1404","attributes":{"url":"https://cdn.holoviz.org/panel/1.2.3/dist/css/listpanel.css"}},{"type":"object","name":"ImportedStyleSheet","id":"p1349","attributes":{"url":"https://cdn.holoviz.org/panel/1.2.3/dist/bundled/theme/default.css"}},{"type":"object","name":"ImportedStyleSheet","id":"p1350","attributes":{"url":"https://cdn.holoviz.org/panel/1.2.3/dist/bundled/theme/native.css"}}],"min_width":700,"margin":0,"sizing_mode":"stretch_width","align":"start","children":[{"type":"object","name":"Spacer","id":"p1352","attributes":{"name":"HSpacer01746","stylesheets":["\n:host(.pn-loading.pn-arc):before, .pn-loading.pn-arc:before {\n  background-image: url(\"data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHN0eWxlPSJtYXJnaW46IGF1dG87IGJhY2tncm91bmQ6IG5vbmU7IGRpc3BsYXk6IGJsb2NrOyBzaGFwZS1yZW5kZXJpbmc6IGF1dG87IiB2aWV3Qm94PSIwIDAgMTAwIDEwMCIgcHJlc2VydmVBc3BlY3RSYXRpbz0ieE1pZFlNaWQiPiAgPGNpcmNsZSBjeD0iNTAiIGN5PSI1MCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjYzNjM2MzIiBzdHJva2Utd2lkdGg9IjEwIiByPSIzNSIgc3Ryb2tlLWRhc2hhcnJheT0iMTY0LjkzMzYxNDMxMzQ2NDE1IDU2Ljk3Nzg3MTQzNzgyMTM4Ij4gICAgPGFuaW1hdGVUcmFuc2Zvcm0gYXR0cmlidXRlTmFtZT0idHJhbnNmb3JtIiB0eXBlPSJyb3RhdGUiIHJlcGVhdENvdW50PSJpbmRlZmluaXRlIiBkdXI9IjFzIiB2YWx1ZXM9IjAgNTAgNTA7MzYwIDUwIDUwIiBrZXlUaW1lcz0iMDsxIj48L2FuaW1hdGVUcmFuc2Zvcm0+ICA8L2NpcmNsZT48L3N2Zz4=\");\n  background-size: auto calc(min(50%, 400px));\n}",{"id":"p1351"},{"id":"p1349"},{"id":"p1350"}],"margin":0,"sizing_mode":"stretch_width","align":"start"}},{"type":"object","name":"Figure","id":"p1360","attributes":{"width":700,"height":300,"margin":[5,10],"sizing_mode":"fixed","align":"start","x_range":{"type":"object","name":"Range1d","id":"p1353","attributes":{"tags":[[["k","k",null]],[]],"start":1.0,"end":11.0,"reset_start":1.0,"reset_end":11.0}},"y_range":{"type":"object","name":"Range1d","id":"p1354","attributes":{"tags":[[["inertia","inertia",null]],{"type":"map","entries":[["invert_yaxis",false],["autorange",false]]}],"start":-16.82270447920522,"end":281.7556119358101,"reset_start":-16.82270447920522,"reset_end":281.7556119358101}},"x_scale":{"type":"object","name":"LinearScale","id":"p1370"},"y_scale":{"type":"object","name":"LinearScale","id":"p1371"},"title":{"type":"object","name":"Title","id":"p1363","attributes":{"text":"Elbow Curve for PCA Data","text_color":"black","text_font_size":"12pt"}},"renderers":[{"type":"object","name":"GlyphRenderer","id":"p1396","attributes":{"data_source":{"type":"object","name":"ColumnDataSource","id":"p1387","attributes":{"selected":{"type":"object","name":"Selection","id":"p1388","attributes":{"indices":[],"line_indices":[]}},"selection_policy":{"type":"object","name":"UnionRenderers","id":"p1389"},"data":{"type":"map","entries":[["k",{"type":"ndarray","array":{"type":"bytes","data":"AQAAAAIAAAADAAAABAAAAAUAAAAGAAAABwAAAAgAAAAJAAAACgAAAAsAAAA="},"shape":[11],"dtype":"int32","order":"little"}],["inertia",{"type":"ndarray","array":{"type":"bytes","data":"CgAmQfwNcEBEVJAi3bxkQPIsl3eTcVdAkoiJ/i7VSECeItBAUQlDQEi8U/V6uDtAuBTaLDMlNUBU5NxBYzUxQPJqkhpScCtAoe9NHWQeJUDHnhDnHR4gQA=="},"shape":[11],"dtype":"float64","order":"little"}]]}}},"view":{"type":"object","name":"CDSView","id":"p1397","attributes":{"filter":{"type":"object","name":"AllIndices","id":"p1398"}}},"glyph":{"type":"object","name":"Line","id":"p1393","attributes":{"tags":["apply_ranges"],"x":{"type":"field","field":"k"},"y":{"type":"field","field":"inertia"},"line_color":"#30a2da","line_width":2}},"selection_glyph":{"type":"object","name":"Line","id":"p1399","attributes":{"tags":["apply_ranges"],"x":{"type":"field","field":"k"},"y":{"type":"field","field":"inertia"},"line_color":"#30a2da","line_width":2}},"nonselection_glyph":{"type":"object","name":"Line","id":"p1394","attributes":{"tags":["apply_ranges"],"x":{"type":"field","field":"k"},"y":{"type":"field","field":"inertia"},"line_color":"#30a2da","line_alpha":0.1,"line_width":2}},"muted_glyph":{"type":"object","name":"Line","id":"p1395","attributes":{"tags":["apply_ranges"],"x":{"type":"field","field":"k"},"y":{"type":"field","field":"inertia"},"line_color":"#30a2da","line_alpha":0.2,"line_width":2}}}}],"toolbar":{"type":"object","name":"Toolbar","id":"p1369","attributes":{"tools":[{"type":"object","name":"WheelZoomTool","id":"p1358","attributes":{"tags":["hv_created"],"zoom_together":"none"}},{"type":"object","name":"HoverTool","id":"p1359","attributes":{"tags":["hv_created"],"renderers":[{"id":"p1396"}],"tooltips":[["k","@{k}"],["inertia","@{inertia}"]]}},{"type":"object","name":"SaveTool","id":"p1382"},{"type":"object","name":"PanTool","id":"p1383"},{"type":"object","name":"BoxZoomTool","id":"p1384","attributes":{"overlay":{"type":"object","name":"BoxAnnotation","id":"p1385","attributes":{"syncable":false,"level":"overlay","visible":false,"left_units":"canvas","right_units":"canvas","bottom_units":"canvas","top_units":"canvas","line_color":"black","line_alpha":1.0,"line_width":2,"line_dash":[4,4],"fill_color":"lightgrey","fill_alpha":0.5}}}},{"type":"object","name":"ResetTool","id":"p1386"}],"active_drag":{"id":"p1383"},"active_scroll":{"id":"p1358"}}},"left":[{"type":"object","name":"LinearAxis","id":"p1377","attributes":{"ticker":{"type":"object","name":"BasicTicker","id":"p1378","attributes":{"mantissas":[1,2,5]}},"formatter":{"type":"object","name":"BasicTickFormatter","id":"p1379"},"axis_label":"inertia","major_label_policy":{"type":"object","name":"AllLabels","id":"p1380"}}}],"below":[{"type":"object","name":"LinearAxis","id":"p1372","attributes":{"ticker":{"type":"object","name":"FixedTicker","id":"p1400","attributes":{"ticks":[1,2,3,4,5,6,7,8,9,10,11],"minor_ticks":[]}},"formatter":{"type":"object","name":"BasicTickFormatter","id":"p1374"},"axis_label":"k","major_label_policy":{"type":"object","name":"AllLabels","id":"p1375"}}}],"center":[{"type":"object","name":"Grid","id":"p1376","attributes":{"axis":{"id":"p1372"},"grid_line_color":null}},{"type":"object","name":"Grid","id":"p1381","attributes":{"dimension":1,"axis":{"id":"p1377"},"grid_line_color":null}}],"min_border_top":10,"min_border_bottom":10,"min_border_left":10,"min_border_right":10,"output_backend":"webgl"}},{"type":"object","name":"Spacer","id":"p1402","attributes":{"name":"HSpacer01749","stylesheets":["\n:host(.pn-loading.pn-arc):before, .pn-loading.pn-arc:before {\n  background-image: url(\"data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHN0eWxlPSJtYXJnaW46IGF1dG87IGJhY2tncm91bmQ6IG5vbmU7IGRpc3BsYXk6IGJsb2NrOyBzaGFwZS1yZW5kZXJpbmc6IGF1dG87IiB2aWV3Qm94PSIwIDAgMTAwIDEwMCIgcHJlc2VydmVBc3BlY3RSYXRpbz0ieE1pZFlNaWQiPiAgPGNpcmNsZSBjeD0iNTAiIGN5PSI1MCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjYzNjM2MzIiBzdHJva2Utd2lkdGg9IjEwIiByPSIzNSIgc3Ryb2tlLWRhc2hhcnJheT0iMTY0LjkzMzYxNDMxMzQ2NDE1IDU2Ljk3Nzg3MTQzNzgyMTM4Ij4gICAgPGFuaW1hdGVUcmFuc2Zvcm0gYXR0cmlidXRlTmFtZT0idHJhbnNmb3JtIiB0eXBlPSJyb3RhdGUiIHJlcGVhdENvdW50PSJpbmRlZmluaXRlIiBkdXI9IjFzIiB2YWx1ZXM9IjAgNTAgNTA7MzYwIDUwIDUwIiBrZXlUaW1lcz0iMDsxIj48L2FuaW1hdGVUcmFuc2Zvcm0+ICA8L2NpcmNsZT48L3N2Zz4=\");\n  background-size: auto calc(min(50%, 400px));\n}",{"id":"p1351"},{"id":"p1349"},{"id":"p1350"}],"margin":0,"sizing_mode":"stretch_width","align":"start"}}]}}],"defs":[{"type":"model","name":"ReactiveHTML1"},{"type":"model","name":"FlexBox1","properties":[{"name":"align_content","kind":"Any","default":"flex-start"},{"name":"align_items","kind":"Any","default":"flex-start"},{"name":"flex_direction","kind":"Any","default":"row"},{"name":"flex_wrap","kind":"Any","default":"wrap"},{"name":"justify_content","kind":"Any","default":"flex-start"}]},{"type":"model","name":"FloatPanel1","properties":[{"name":"config","kind":"Any","default":{"type":"map"}},{"name":"contained","kind":"Any","default":true},{"name":"position","kind":"Any","default":"right-top"},{"name":"offsetx","kind":"Any","default":null},{"name":"offsety","kind":"Any","default":null},{"name":"theme","kind":"Any","default":"primary"},{"name":"status","kind":"Any","default":"normalized"}]},{"type":"model","name":"GridStack1","properties":[{"name":"mode","kind":"Any","default":"warn"},{"name":"ncols","kind":"Any","default":null},{"name":"nrows","kind":"Any","default":null},{"name":"allow_resize","kind":"Any","default":true},{"name":"allow_drag","kind":"Any","default":true},{"name":"state","kind":"Any","default":[]}]},{"type":"model","name":"drag1","properties":[{"name":"slider_width","kind":"Any","default":5},{"name":"slider_color","kind":"Any","default":"black"},{"name":"value","kind":"Any","default":50}]},{"type":"model","name":"click1","properties":[{"name":"terminal_output","kind":"Any","default":""},{"name":"debug_name","kind":"Any","default":""},{"name":"clears","kind":"Any","default":0}]},{"type":"model","name":"FastWrapper1","properties":[{"name":"object","kind":"Any","default":null},{"name":"style","kind":"Any","default":null}]},{"type":"model","name":"NotificationAreaBase1","properties":[{"name":"js_events","kind":"Any","default":{"type":"map"}},{"name":"position","kind":"Any","default":"bottom-right"},{"name":"_clear","kind":"Any","default":0}]},{"type":"model","name":"NotificationArea1","properties":[{"name":"js_events","kind":"Any","default":{"type":"map"}},{"name":"notifications","kind":"Any","default":[]},{"name":"position","kind":"Any","default":"bottom-right"},{"name":"_clear","kind":"Any","default":0},{"name":"types","kind":"Any","default":[{"type":"map","entries":[["type","warning"],["background","#ffc107"],["icon",{"type":"map","entries":[["className","fas fa-exclamation-triangle"],["tagName","i"],["color","white"]]}]]},{"type":"map","entries":[["type","info"],["background","#007bff"],["icon",{"type":"map","entries":[["className","fas fa-info-circle"],["tagName","i"],["color","white"]]}]]}]}]},{"type":"model","name":"Notification","properties":[{"name":"background","kind":"Any","default":null},{"name":"duration","kind":"Any","default":3000},{"name":"icon","kind":"Any","default":null},{"name":"message","kind":"Any","default":""},{"name":"notification_type","kind":"Any","default":null},{"name":"_destroyed","kind":"Any","default":false}]},{"type":"model","name":"TemplateActions1","properties":[{"name":"open_modal","kind":"Any","default":0},{"name":"close_modal","kind":"Any","default":0}]},{"type":"model","name":"BootstrapTemplateActions1","properties":[{"name":"open_modal","kind":"Any","default":0},{"name":"close_modal","kind":"Any","default":0}]},{"type":"model","name":"MaterialTemplateActions1","properties":[{"name":"open_modal","kind":"Any","default":0},{"name":"close_modal","kind":"Any","default":0}]}]}};
  var render_items = [{"docid":"9d7f11e4-e358-4b0d-98bf-e03642e8de44","roots":{"p1348":"dcfade00-8e5c-4a3d-837b-bce921abb21a"},"root_ids":["p1348"]}];
  var docs = Object.values(docs_json)
  if (!docs) {
    return
  }
  const py_version = docs[0].version.replace('rc', '-rc.').replace('.dev', '-dev.')
  const is_dev = py_version.indexOf("+") !== -1 || py_version.indexOf("-") !== -1
  function embed_document(root) {
    var Bokeh = get_bokeh(root)
    Bokeh.embed.embed_items_notebook(docs_json, render_items);
    for (const render_item of render_items) {
      for (const root_id of render_item.root_ids) {
	const id_el = document.getElementById(root_id)
	if (id_el.children.length && (id_el.children[0].className === 'bk-root')) {
	  const root_el = id_el.children[0]
	  root_el.id = root_el.id + '-rendered'
	}
      }
    }
  }
  function get_bokeh(root) {
    if (root.Bokeh === undefined) {
      return null
    } else if (root.Bokeh.version !== py_version && !is_dev) {
      if (root.Bokeh.versions === undefined || !root.Bokeh.versions.has(py_version)) {
	return null
      }
      return root.Bokeh.versions.get(py_version);
    } else if (root.Bokeh.version === py_version) {
      return root.Bokeh
    }
    return null
  }
  function is_loaded(root) {
    var Bokeh = get_bokeh(root)
    return (Bokeh != null && Bokeh.Panel !== undefined)
  }
  if (is_loaded(root)) {
    embed_document(root);
  } else {
    var attempts = 0;
    var timer = setInterval(function(root) {
      if (is_loaded(root)) {
        clearInterval(timer);
        embed_document(root);
      } else if (document.readyState == "complete") {
        attempts++;
        if (attempts > 200) {
          clearInterval(timer);
	  var Bokeh = get_bokeh(root)
	  if (Bokeh == null || Bokeh.Panel == null) {
            console.warn("Panel: ERROR: Unable to run Panel code because Bokeh or Panel library is missing");
	  } else {
	    console.warn("Panel: WARNING: Attempting to render but not all required libraries could be resolved.")
	    embed_document(root)
	  }
        }
      }
    }, 25, root)
  }
})(window);</script>

The second elbow curve for PCA data displays a lower inertia value compared to the first curve for the original data. This suggests that using fewer features reduces the sum of squared distances within clusters, indicating better clustering performance and tighter grouping of data points.
Cluster Scatter Plot Analysis:
cluster1
cluster2

Original Data (Cluster Graph 1): Overlapping clusters with no clear separation or distinctiveness, indicating a potential failure to capture underlying patterns.

PCA Data (Cluster Graph 2): Non-overlapping clusters with clear separation, showcasing four distinct clusters. Using fewer features through PCA potentially reduces noise and reveals more distinct patterns, resulting in meaningful and separable clusters.

**Conclusion
The utilization of fewer features (PCA data) for K-Means clustering of cryptocurrency data has positively impacted the results. It has led to well-defined and separable clusters compared to using the original data. The reduction in features through PCA likely emphasizes essential patterns, reduces noise, and enhances the accuracy of clustering results.

