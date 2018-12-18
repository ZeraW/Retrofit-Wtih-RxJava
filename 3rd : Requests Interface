public interface RetrofitAPI {
    @FormUrlEncoded
    @POST("users")
    Single<Users> addUsers(@Field("name")String name, @Field("job")String job);

    @GET("users?page=2")
    Observable<AllUsers> getUsers();

    @GET("users?page=2")
    Single<AllUsers> getUsers2();
}
