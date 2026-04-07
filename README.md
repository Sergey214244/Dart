import 'package:dash/dash.dart';

part 'provider.g.dart';

@BlocProvider.register(MySampleBloc)
@BlocProvider.register(MyOtherBloc)
abstract class Provider {}
