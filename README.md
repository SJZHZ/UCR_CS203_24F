# CS203_UCR_24F
## Dealing with Assignment
1. Update before modifying
    ```python
    ! ./fix-repo
    ! ./pull-updates
    ```
2. Finish the assignment
3. Extract the answer cells
    ```python
    !cs203 turnin assignment.ipynb
    !ls -lh assignment.turnin.ipynb
    ```
4. Commit and push
    ```python
    !git add -f assignment.turnin.ipynb
    !git commit -am "Yay! I am ready to turn in!"
    !git push
    ```
5. Submit and grade
  [UCR_CS203_gradescope](https://www.gradescope.com/courses/863120)
## Git Skills
```bash
git submodule update --remote
```
