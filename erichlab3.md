## Erich Then - Lab Report 3

### Failure inducing input for reverseInPlace method:  

```
{
 @Test
  public void testReverseInPlace1() {
    int[] input = {4, 4, 3};
    int[] expected = {3, 4, 4};
    ArrayExamples.reverseInPlace(input);
    assertArrayEquals(expected, input);
  }
}
```

## Non-failure inducing input for reverseInPlace method: 

```
{
  @Test
  public void testReverseInPlace2() {
    int[] input = {1, 3, 1};
    int[] expected = {1,3,1};
    ArrayExamples.reverseInPlace(input);
    assertArrayEquals(expected, input);
    
  }
}
```

## Output of running these two tests:  





