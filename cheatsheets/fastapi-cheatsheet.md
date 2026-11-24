# FastAPI Framework Cheatsheet

Router setup and path operations:
- `app = FastAPI(lifespan=lifespan)`
- `@router.get('/items/{item_id}', response_model=ItemOut)`
- `async def get_db() -> AsyncGenerator[AsyncSession, None]:`
