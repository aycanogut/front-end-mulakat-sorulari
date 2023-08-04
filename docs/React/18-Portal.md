React portal, bir bileşenin başka bir bileşenin alt ağacı dışındaki bir DOM düğümüne eklenmesine izin veren bir React özelliğidir. Bu, DOM hiyerarşisinde daha yüksek bir düzeyde bir bileşen oluşturmak istediğiniz durumlarda kullanışlıdır.

Örneğin, bir modal bileşeni oluşturduğunuzu varsayalım. Modal, genellikle uygulamanızın kök bileşeninden bağımsız olarak görüntülenir ve bu nedenle DOM ağacında kök düzeyinde bir düğüme eklenmelidir. Ancak, normalde bir bileşen yalnızca ebeveyn bileşeninin alt ağacına eklenir.

React portal, bu sorunu çözmek için kullanılabilir. Portal kullanarak, bir bileşeni modal gibi herhangi bir DOM düğümüne eklenebilir. Bu, bileşen hiyerarşisinde herhangi bir yerdeki bir bileşen için geçerlidir.