in RouteCollection.php line 179
at RouteCollection->match(object(Request)) in Router.php line 533
at Router->findRoute(object(Request)) in Router.php line 512
at Router->dispatchToRoute(object(Request)) in Router.php line 498
at Router->dispatch(object(Request)) in Kernel.php line 174
at Kernel->Illuminate\Foundation\Http\{closure}(object(Request)) in Pipeline.php line 30
at Pipeline->Illuminate\Routing\{closure}(object(Request)) in TransformsRequest.php line 30
at TransformsRequest->handle(object(Request), object(Closure)) in Pipeline.php line 148
at Pipeline->Illuminate\Pipeline\{closure}(object(Request)) in Pipeline.php line 53
at Pipeline->Illuminate\Routing\{closure}(object(Request)) in TransformsRequest.php line 30
at TransformsRequest->handle(object(Request), object(Closure)) in Pipeline.php line 148
at Pipeline->Illuminate\Pipeline\{closure}(object(Request)) in Pipeline.php line 53
at Pipeline->Illuminate\Routing\{closure}(object(Request)) in ValidatePostSize.php line 27
at ValidatePostSize->handle(object(Request), object(Closure)) in Pipeline.php line 148
at Pipeline->Illuminate\Pipeline\{closure}(object(Request)) in Pipeline.php line 53
at Pipeline->Illuminate\Routing\{closure}(object(Request)) in CheckForMaintenanceMode.php line 46
at CheckForMaintenanceMode->handle(object(Request), object(Closure)) in Pipeline.php line 148
at Pipeline->Illuminate\Pipeline\{closure}(object(Request)) in Pipeline.php line 53
at Pipeline->Illuminate\Routing\{closure}(object(Request)) in Pipeline.php line 102
at Pipeline->then(object(Closure)) in Kernel.php line 149
at Kernel->sendRequestThroughRouter(object(Request)) in Kernel.php line 116
at Kernel->handle(object(Request)) in index.php line 54
