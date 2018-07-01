```
<?php $currGroup = get_object_vars($this->user) ['row']['group'];
                      if ($currGroup == "administrator"): ?>
                      <a href="<?php $this->options->adminUrl('write-post.php?cid=' . $this->cid ); ?>">后台编辑</a>
<?php endif; ?
```
