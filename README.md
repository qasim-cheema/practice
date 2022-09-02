# practice


public static <D> Result<D> fromEntity(D entity) {
    return withDate(new Result<>(entity));
  }
