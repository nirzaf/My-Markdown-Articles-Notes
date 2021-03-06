</pre>

A Hashtable is a collection of key/value pairs that are arranged based on the hash code of the key. Or in other words, a Hashtable is used to create a collection which uses a hash table for storage. It is the non-generic type of collection which is defined in _System.Collections_ namespace. In Hashtable, key objects must be immutable as long as they are used as keys in the Hashtable.


#### Hashtable Vs Dictionary

<style>.math-table{border-collapse:collapse;width:100%}.math-table td{border:1px solid #5fb962;text-align:left!important;padding:8px}.math-table th{border:1px solid #5fb962;padding:8px}.math-table tr&gt;th{background-color:#c6ebd9;vertical-align:middle}.math-table tr:nth-child(odd){background-color:#fff}</style>

<table class="math-table">

<tbody>

<tr>
<th style="background-color:#c6ebd9">Hashtable</th>
<th style="background-color:#c6ebd9">Dictionary</th>

</tr>

</tbody>

<tbody>

<tr>

<td>A Hashtable is a non-generic collection.</td>

<td>A Dictionary is a generic collection.</td>

</tr>

<tr>

<td>Hashtable is defined under System.Collections namespace.</td>

<td>Dictionary is defined under System.Collections.Generic namespace.</td>

</tr>

<tr>

<td>In Hashtable, you can store key/value pairs of the same type or of the different type.</td>

<td>In Dictionary, you can store key/value pairs of same type.</td>

</tr>

<tr>

<td>In Hashtable, there is no need to specify the type of the key and value.</td>

<td>In Dictionary, you must specify the type of key and value.</td>

</tr>

<tr>

<td>The data retrieval is slower than Dictionary due to boxing/ unboxing.</td>

<td>The data retrieval is faster than Hashtable due to no boxing/ unboxing.</td>

</tr>

<tr>

<td>In Hashtable, if you try to access a key that doesn’t present in the given Hashtable, then it will give null values.</td>

<td>In Dictionary, if you try to access a key that doesn’t present in the given Dictionary, then it will give error.</td>

</tr>

<tr>

<td>It is thread safe.</td>

<td>It is also thread safe but only for public static members.</td>

</tr>

<tr>

<td>It doesn’t maintain the order of stored values.</td>

<td>It always maintain the order of stored values.</td>

</tr>

</tbody>

</table>

<div class="textBasedMannualAds_2">

</div>


</div>

</div>

</div>

</article>


