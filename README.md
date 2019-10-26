/*
Change Currency Symbol for WooCommerce
Lets you set a your symbol for the currently selected currency.
*/

function change_currency_symbol( $currency_symbol, $currency ) {
    $symbol = 'USD';
    return $symbol;
}
add_filter('woocommerce_currency_symbol', 'change_currency_symbol', 10, 2);
