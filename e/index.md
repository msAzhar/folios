#   Minimum Kapsayan Ağaçlar

.fx: first

Azhar MURZAEVA

Şeymanur ÇALIK

`ALGORİTMALAR`

Öğretmen: Nurettin ŞENYER

Mayıs 2016

![Çizge Örneği](r.png)

---

###İçerik
- Graph(Çizge) nedir?
- Ağaç nedir?
- Kullanılan alanlar
- Minimum Kapsayan Ağaçlar nedir?
- Kullanılan alanlar
- Prim Algoritması
- Kruskal Algoritması




###Graph(Çizge) nedir?

- `Çizge` veya `Graf`, düğümler ve bu düğümleri birbirine bağlayan kenarlardan oluşan bir tür ağ yapısıdır. Örnek bir çizge:

<img src="pics/g.png" width=300 height=170>





###Ağaç(Tree) Nedir?

- Eğer ki, graf bağlı bir graf ise ve bu graf hiç döngü içermiyorsa, bu graf türüne Ağaç denmektedir. Örnek bir Ağaç:

<img src="pics/a.svg" >


###Kullanılan Alanlar

- Matematikte
- Fizikte
- Biyolojide


<img src="pics/a.svg" >


###Minimum Kapsayan Ağaç Nedir?

- Düğümlerinin aralarında bağlantı olmayan bir graf verilsin. Bu graf için öyle bir ağaç bulunmalı ki, onun bütün güğümlerine bağlı olsun ve aynı anda olası olan bütün maliyetlerinin en azına sahip olsun. İşte böyle ağaca minimum kapsayan ağaç denmektedir.

<img src="pics/mst.png" width=400 height=284>


####Minimum Kapsayan Ağaç

- Bir çizge(graf) birçok kapsayan ağacı içerebilir. Örneğin, 
4 düğümlü bir çizge 16 tane kapsayan ağaca sahiptir:
<table>
<tr>
<td><img src="pics/gnm1.png" style="float: left"><p></td>

<td><img src="pics/gnm2.png" style="float: left"></td>

<td><img src="pics/gnm3.png" style="float: left"></td>

<td><img src="pics/gnm4.png" style="float: left"></td>
</tr>
<tr>
<td><img src="pics/gnm5.png" style="float: left"></td>

<td><img src="pics/gnm6.png" style="float: left"></td>

<td><img src="pics/gnm7.png" style="float: left"></td>

<td><img src="pics/gnm8.png" style="float: left"></td>
</tr>
<tr>
<td><img src="pics/gnm9.png" style="float: left"></td>

<td><img src="pics/gnm10.png" style="float: left"></td>

<td><img src="pics/gnm11.png" style="float: left"></td>

<td><img src="pics/gnm12.png" style="float: left"></td>
</tr>
<tr>
<td><img src="pics/gnm13.png" style="float: left"></td>

<td><img src="pics/gnm14.png" style="float: left"></td>

<td><img src="pics/gnm15.png" style="float: left"></td>

<td><img src="pics/gnm16.png" style="float: left"></td>
</tr>
</table>


####Minimum Kapsayan Ağaç(Devamı)

Minimum kapsayan ağaç bulmak için çeşitli algoritmalar vardır. Bunlardan en ünlü olan bazılar aşağıdakilerdir: 

- Prim Algoritması
- Kruskal Algoritması
- Boruvka(Sollin) Algoritması


####Prim Algoritması

Bu algoritma 1930 yılında matematikçi Vojtech Jarnik tarafından bulunmuştur. Daha sonra bağımsız olarak 1957'de bilgisayar bilimcisi Robert C. Prim ve 1959'da Dijkstra tarafından tekrar bulunmuştur. 

####Prim Algoritması(Devamı)

<img src="pics/o.png" style="float: center" width=400 height=336>


####Prim Algoritması(Devamı)

<img src="pics/p1.png" style="float: center" width=400 height=336>

####Prim Algoritması(Devamı)

<img src="pics/p2.png" style="float: center" width=400 height=336>

####Prim Algoritması(Devamı)

<img src="pics/p3.png" style="float: center" width=400 height=336>

####Prim Algoritması(Devamı)

<img src="pics/p4.png" style="float: center" width=400 height=336>

####Prim Algoritması(Devamı)

<img src="pics/p5.png" style="float: center" width=400 height=336>

####Prim Algoritması(Devamı)

<img src="pics/p6.png" style="float: center" width=400 height=336>

####Prim Algoritması(Devamı)

<img src="pics/p7.png" style="float: center" width=400 height=336>


####Kruskal Algoritması

Kruskal algoritması Joseph Kruskal tarafından geliştirilmiş ve ilk kez 1956 yılında anlatılmıştır. 
Kruskal algoritması her seferinde en iyi kenarın seçilmesi esasına dayalıdır.


- n kenarlı bir graf için herhangi bir düğümle başlanır ve en kısa yol buna eklenir. 
- Döngü oluşturmayacak şekilde (n-1) kenar eklenene kadar devam edilir. 
- Aynı değerli kenarlarda seçim keyfi yapılabilir.
- Düğümlerin birleştirilme işlemine en az maliyetli kenardan başlanır, kalan kenarlar arasından en az maliyetlisi seçilerek devam edilir.


####Kruskal Algoritması(Devamı)

<img src="pics/o.png" style="float: center" width=400 height=336>


####Kruskal Algoritması(Devamı)

<img src="pics/k1.png" style="float: center" width=400 height=336>


####Kruskal Algoritması(Devamı)

<img src="pics/k2.png" style="float: center" width=400 height=336>


####Kruskal Algoritması(Devamı)

<img src="pics/k3.png" style="float: center" width=400 height=336>

####Kruskal Algoritması(Devamı)

<img src="pics/k4.png" style="float: center" width=400 height=336>

####Kruskal Algoritması(Devamı)

<img src="pics/k5.png" style="float: center" width=400 height=336>

####Kruskal Algoritması(Devamı)

<img src="pics/k6.png" style="float: center" width=400 height=336>

####Kruskal Algoritması(Devamı)
 def kruskal(graph):
    for vertice in graph['vertices']:
	make_set(vertice)
	minimum_spanning_tree = set()
	edges = list(graph['edges'])
	edges.sort()
	#print edges
    for edge in edges:
	weight, vertice1, vertice2 = edge
	if find(vertice1) != find(vertice2):
	    union(vertice1, vertice2)
	    minimum_spanning_tree.add(edge)
	    
    return sorted(minimum_spanning_tree)

####Kaynaklar

- https://en.wikipedia.org/wiki/Graph
- https://en.wikipedia.org/wiki/Kruskal%27s_algorithm
- https://tr.wikipedia.org/wiki/Prim_algoritmas%C4%B1
- http://www.stoimen.com/blog/2012/11/19/computer-algorithms-prims-minimum-spanning-tree/
-https://www.youtube.com/watch?v=8fJgkVpxbQg
- https://www.youtube.com/watch?v=5XkK88VEILk
- https://www.youtube.com/watch?v=Pn874kEc3IA



####Minimum Kapsayan Ağaçlar

- Dikkatiniz için Teşekkürler...
- Sorular???
<img src="r.png" style="float: center">

