+++
date = '{{ .Date }}'
draft = true
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
+++


<div class="date-footer">
    {{ .Date | time.Format ":date_medium" }}
</div>
