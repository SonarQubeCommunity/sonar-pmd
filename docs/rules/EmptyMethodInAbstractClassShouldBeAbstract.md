# EmptyMethodInAbstractClassShouldBeAbstract
**Category:** `pmd`<br/>
**Rule Key:** `pmd:EmptyMethodInAbstractClassShouldBeAbstract`<br/>


-----

An empty method in an abstract class should be abstract instead, as developer may rely on this empty implementation rather than code the appropriate one.
<pre>
public abstract class ShouldBeAbstract
{
  public Object couldBeAbstract()
  {
  // Should be abstract method ?
    return null;
  }

  public void couldBeAbstract()
  {
  }
}
</pre>
