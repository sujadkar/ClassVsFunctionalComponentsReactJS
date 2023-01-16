# Class Vs FunctionalComponents ReactJS


![image](https://user-images.githubusercontent.com/16307466/212704576-287ec016-90b3-4349-9aa2-0dc4bbf6c953.png)




<h2>Side effects is Functional Components useEffect()</h2>

<h2>Class based componenets can't use React Hooks</h2>

<h2>Comparion Functional React Hooks vs Class Componenent Life Cycle method</h2>

<table>
<tr>
  <th>Class Componenet</th>
  <th>Comment</th>
  <th>Functional Compoenent</th>
</tr>
<tr>
  <td>componenetDidMount()</td>
  <td>Called once component mounted(Was evaluated and rendered)</td>
  <td>useEffect(...,[]) </td>
</tr>
<tr>
  <td>componenetDidUpdate()</td>
  <td>Called once component updated(Was evaluated and rendered)</td>
  <td>useEffect(...,[dependencies]) </td>
</tr>
<tr>
  <td>componenetWillUnmount()</td>
  <td>Called right before component is unmounted(removed from DOM)</td>
  <td>useEffect(() => return () {...cleanup code},[]) </td>
</tr>
</table>

<hr/>
<ol>
<h2>Use class based if</h2>
<li><h3>We prefer them</h3></li>
<li><h3>We are working on exsisting project or in a Team where they are getting used</h3></li>
<li><h3>We are using ErrorBoundary</h3></li>
</ol>

<hr/>


<h2>What is Error Boundary?<h2>
<h3>Error boundaries are React components that catch JavaScript errors anywhere in their child component tree, log those errors, and display a fallback UI 
instead of the component tree that crashed.</h3>

<h2>Use componentDidCatch() to log error information.<h2>

<h3>Note</h3>
<h3>Error boundaries do not catch errors for:</h3>
<ul>
 <li>Event handlers (learn more)</li>
 <li>Asynchronous code (e.g. setTimeout or requestAnimationFrame callbacks)</li>
 <li>Server side rendering</li>
 <li>Errors thrown in the error boundary itself (rather than its children)</li>
</ul>


Example : 

![image](https://user-images.githubusercontent.com/16307466/212708666-9f714201-34f3-432c-9c27-33cce6d54699.png)

![image](https://user-images.githubusercontent.com/16307466/212708730-4c8781be-ac40-4c8f-8ecc-b85648b61738.png)



    

        
        
        
        





