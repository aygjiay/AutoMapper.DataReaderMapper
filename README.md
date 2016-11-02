# AutoMapper.DataReaderMapper

An unofficial branch of the original <a href="https://github.com/AutoMapper/AutoMapper.Data">Jimmy Bogard AutoMapper.Data</a> it has been modified supporting last AutoMapper version working in Visual Studio 2012

Available as Nuget package <a href="https://www.nuget.org/packages/AutoMapper.DataReaderMapper/">AutoMapper.DataReaderMapper</a>

Using:

```
AutoMapper.Mapper.Initialize(cfg =>
{
   AutoMapper.Mappers.MapperRegistry.Mappers.Add(new AutoMapper.DataReaderMapper.DataReaderMapper(AutoMapper.Mapper.Engine));

   cfg.CreateMap(typeof(IDataReader), typeof(TargetClass));
});
```
