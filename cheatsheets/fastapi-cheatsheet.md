# FastAPI Framework Cheatsheet

Router setup and path operations:
- `app = FastAPI(lifespan=lifespan)`
- `@router.get('/items/{item_id}', response_model=ItemOut)`
- `async def get_db() -> AsyncGenerator[AsyncSession, None]:`


## Practical Idioms and Recipes

Background tasks and exception handling:
- `background_tasks.add_task(send_email, to=user.email)`
- `@app.exception_handler(HTTPException)`
