### Vectors and the Geometry of Space

The 3 **coordinate planes** divide space into 8 cells called **octant**, the $(+,+,+)$ octant is called the **first octant**.

![1555228627252](assets/1555228627252.png)

The distance between two point is 
$$
\left|P_{1} P_{2}\right|=\sqrt{\left(x_{2}-x_{1}\right)^{2}+\left(y_{2}-y_{1}\right)^{2}+\left(z_{2}-z_{1}\right)^{2}}
$$
The cross product $u\times v$ is:
$$
\mathbf{u} \times \mathbf{v}=(|\mathbf{u}||\mathbf{v}| \sin \theta) \mathbf{n}
$$
![1555228987738](assets/1555228987738.png)

Hence nonzero vectors $u$ and $v$ are parallel if and only if $u \times v=0$.



Cross product has some properties
$$
\begin{array}{ll}{\text { 1. }(r \mathbf{u}) \times(s \mathbf{v})=(r s)(\mathbf{u} \times \mathbf{v})} & {\text { 2. } \mathbf{u} \times(\mathbf{v}+\mathbf{w})=\mathbf{u} \times \mathbf{v}+\mathbf{u} \times \mathbf{w}} \\ {3 . \mathbf{v} \times \mathbf{u}=-(\mathbf{u} \times \mathbf{v})} & {\text { 4. }(\mathbf{v}+\mathbf{w}) \times \mathbf{u}=\mathbf{v} \times \mathbf{u}+\mathbf{w} \times \mathbf{u}} \\ {\text { 5. } \mathbf{0} \times \mathbf{u}=\mathbf{0}} & {\text { 6. } \mathbf{u} \times(\mathbf{v} \times \mathbf{w})=(\mathbf{u} \cdot \mathbf{w}) \mathbf{v}-(\mathbf{u} \cdot \mathbf{v}) \mathbf{w}}\end{array}
$$
The parallelogram determined by $u$ and $v$ is $u \times v​$

![1555229407913](assets/1555229407913.png)

If $\mathbf{u}=u_{1} \mathbf{i}+u_{2} \mathbf{j}+u_{3} \mathbf{k}$ and $\mathbf{v}=v_{1} \mathbf{i}+v_{2} \mathbf{j}+v_{3} \mathbf{k}$ then
$$
\mathbf{u} \times \mathbf{v}=\left| \begin{array}{ccc}{\mathbf{i}} & {\mathbf{j}} & {\mathbf{k}} \\ {u_{1}} & {u_{2}} & {u_{3}} \\ {v_{1}} & {v_{2}} & {v_{3}}\end{array}\right|
$$
Hence
$$
u\times v \cdot w=\left| \begin{array}{ccc}{\mathbf{i}} & {\mathbf{j}} & {\mathbf{k}} \\ {u_{1}} & {u_{2}} & {u_{3}} \\ {v_{1}} & {v_{2}} & {v_{3}}\end{array}\right|\cdot (w_1\mathbf{i}+w_2\mathbf{j}+w_3\mathbf{k})=\left| \begin{array}{lll}{u_{1}} & {u_{2}} & {u_{3}} \\ {v_{1}} & {v_{2}} & {v_{3}} \\ {w_{1}} & {w_{2}} & {w_{3}}\end{array}\right|
$$
which is the volume of a parallelepiped determined by $u,v,,$

![1555230933438](assets/1555230933438.png)