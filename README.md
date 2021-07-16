# kubernetes-pod vs deployment
Pod Vs Deployment in Kubernetes
<p>Kubernetes has three&nbsp;<strong>Object Types</strong>&nbsp;you should know about:</p>
<ul>
<li><strong>Pods</strong>&nbsp;- runs one or more closely related containers</li>
<li><strong>Services</strong>&nbsp;- sets up networking in a Kubernetes cluster</li>
<li><strong>Deployment</strong>&nbsp;- Maintains a set of identical pods, ensuring that they have the correct config and that the right number of them exist.</li>
</ul>
<p>Ref: <a href="https://stackoverflow.com/questions/41325087/what-is-the-difference-between-a-pod-and-a-deployment">https://stackoverflow.com/questions/41325087/what-is-the-difference-between-a-pod-and-a-deployment</a>&nbsp;</p>
<table style="border-collapse: collapse; width: 100%; height: 68px;" border="1">
<tbody>
<tr style="height: 17px;">
<td style="width: 50%; height: 17px;"><strong>POD</strong></td>
<td style="width: 50%; height: 17px;"><strong>Deployment</strong></td>
</tr>
<tr style="height: 17px;">
<td style="width: 50%; height: 17px;">Pods that run a single container</td>
<td style="width: 50%; height: 17px;">Can run set of pods</td>
</tr>
<tr style="height: 17px;">
<td style="width: 50%; height: 17px;">Updates not possible</td>
<td style="width: 50%; height: 17px;">Updates are possible</td>
</tr>
<tr style="height: 17px;">
<td style="width: 50%; height: 17px;">Pod crashes not able recover</td>
<td style="width: 50%; height: 17px;">When create a deployment, replcia set is created(which manages pod)</td>
</tr>
<tr>
<td style="width: 50%;">Rollback and rollout is not avaliable</td>
<td style="width: 50%;">rollout and rollback available</td>
</tr>
</tbody>
</table>
