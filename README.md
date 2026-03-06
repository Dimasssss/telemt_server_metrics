# Server Metrics 2026-03-06 13:36:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 11686.2 (3h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 355067
telemt_connections_bad_total 1661
telemt_handshake_timeouts_total 1934
telemt_upstream_connect_attempt_total 4966
telemt_upstream_connect_success_total 4931
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 4945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2137
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 607
telemt_me_reconnect_success_total 599
telemt_me_reader_eof_total 627
telemt_me_idle_close_by_peer_total 627
telemt_me_route_drop_no_conn_total 114138
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1941
telemt_desync_full_logged_total 462
telemt_desync_suppressed_total 1479
telemt_desync_frames_bucket_total{bucket="1_2"} 445
telemt_desync_frames_bucket_total{bucket="3_10"} 663
telemt_desync_frames_bucket_total{bucket="gt_10"} 833
telemt_pool_swap_total 2
telemt_pool_force_close_total 83
telemt_me_writer_removed_unexpected_total 627
telemt_me_writer_restored_same_endpoint_total 593
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 290665
telemt_user_connections_current{user="hello"} 1274
telemt_user_octets_from_client{user="hello"} 5478061868 (5.10 GB)
telemt_user_octets_to_client{user="hello"} 123064183564 (114.61 GB)
telemt_user_unique_ips_current{user="hello"} 312
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 11686.2 (3h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131886
telemt_connections_bad_total 814
telemt_handshake_timeouts_total 4256
telemt_upstream_connect_attempt_total 5159
telemt_upstream_connect_success_total 5144
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 5159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2764
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 75
telemt_me_reconnect_attempts_total 556
telemt_me_reconnect_success_total 550
telemt_me_reader_eof_total 588
telemt_me_idle_close_by_peer_total 588
telemt_me_route_drop_no_conn_total 57934
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 429
telemt_desync_full_logged_total 149
telemt_desync_suppressed_total 280
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 156
telemt_desync_frames_bucket_total{bucket="gt_10"} 202
telemt_pool_swap_total 3
telemt_pool_force_close_total 94
telemt_me_writer_removed_unexpected_total 588
telemt_me_writer_restored_same_endpoint_total 550
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 119584
telemt_user_connections_current{user="hello"} 390
telemt_user_octets_from_client{user="hello"} 1275141120 (1.19 GB)
telemt_user_octets_to_client{user="hello"} 56726334420 (52.83 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 11686.0 (3h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 280223
telemt_connections_bad_total 4631
telemt_handshake_timeouts_total 27299
telemt_upstream_connect_attempt_total 6872
telemt_upstream_connect_success_total 6835
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 6865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3149
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 85
telemt_me_reconnect_attempts_total 1623
telemt_me_reconnect_success_total 1616
telemt_me_reader_eof_total 1695
telemt_me_idle_close_by_peer_total 1695
telemt_me_route_drop_no_conn_total 129817
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 444
telemt_desync_full_logged_total 127
telemt_desync_suppressed_total 317
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 189
telemt_desync_frames_bucket_total{bucket="gt_10"} 156
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 1696
telemt_me_writer_restored_same_endpoint_total 1611
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 238750
telemt_user_connections_current{user="hello"} 610
telemt_user_octets_from_client{user="hello"} 2370163412 (2.21 GB)
telemt_user_octets_to_client{user="hello"} 76804401024 (71.53 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 11002.1 (3h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158834
telemt_connections_bad_total 34827
telemt_handshake_timeouts_total 2979
telemt_upstream_connect_attempt_total 5591
telemt_upstream_connect_success_total 5591
telemt_upstream_connect_attempts_per_request{bucket="1"} 5591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2366
telemt_me_keepalive_timeout_total 69
telemt_me_reconnect_attempts_total 760
telemt_me_reconnect_success_total 753
telemt_me_reader_eof_total 765
telemt_me_idle_close_by_peer_total 765
telemt_me_route_drop_no_conn_total 66172
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 192
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_swap_total 3
telemt_pool_force_close_total 135
telemt_me_writer_removed_unexpected_total 765
telemt_me_writer_restored_same_endpoint_total 753
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 118609
telemt_user_connections_current{user="hello"} 460
telemt_user_octets_from_client{user="hello"} 1436252340 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 48431264364 (45.11 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 11686.3 (3h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216249
telemt_connections_bad_total 7689
telemt_handshake_timeouts_total 2407
telemt_upstream_connect_attempt_total 4009
telemt_upstream_connect_success_total 4002
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1770
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 258
telemt_me_reconnect_success_total 250
telemt_me_reader_eof_total 257
telemt_me_idle_close_by_peer_total 257
telemt_me_route_drop_no_conn_total 111838
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 331
telemt_desync_full_logged_total 112
telemt_desync_suppressed_total 219
telemt_desync_frames_bucket_total{bucket="1_2"} 132
telemt_desync_frames_bucket_total{bucket="3_10"} 104
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 3
telemt_pool_force_close_total 111
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 258
telemt_me_writer_restored_same_endpoint_total 249
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 194580
telemt_user_connections_current{user="hello"} 613
telemt_user_octets_from_client{user="hello"} 13860958276 (12.91 GB)
telemt_user_octets_to_client{user="hello"} 111952564692 (104.26 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 88
```