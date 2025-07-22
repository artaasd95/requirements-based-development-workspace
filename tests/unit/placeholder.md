# Unit Tests

<!-- Unit tests for individual modules/functions -->
<!-- Target: ≥ 80% code coverage -->

## Structure:
```
unit/
├── test_controllers/
├── test_services/
├── test_models/
├── test_repositories/
└── test_utils/
```

## Testing Guidelines:
- Test individual functions/methods in isolation
- Use mocking for external dependencies
- Follow AAA pattern (Arrange, Act, Assert)
- Write descriptive test names
- Include edge cases and error scenarios

## Example Test Structure:
```python
def test_function_name_should_return_expected_result():
    # Arrange
    input_data = "test_input"
    expected_result = "expected_output"
    
    # Act
    result = function_under_test(input_data)
    
    # Assert
    assert result == expected_result
```