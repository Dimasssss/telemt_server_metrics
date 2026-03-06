# Server Metrics 2026-03-06 15:25:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 18186.1 (5h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 539303
telemt_connections_bad_total 4862
telemt_handshake_timeouts_total 2789
telemt_upstream_connect_attempt_total 9272
telemt_upstream_connect_success_total 9214
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 9238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4869
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4286
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 123
telemt_me_reconnect_attempts_total 1871
telemt_me_reconnect_success_total 1860
telemt_me_reader_eof_total 1956
telemt_me_idle_close_by_peer_total 1956
telemt_me_route_drop_no_conn_total 193959
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 2873
telemt_desync_full_logged_total 704
telemt_desync_suppressed_total 2169
telemt_desync_frames_bucket_total{bucket="1_2"} 690
telemt_desync_frames_bucket_total{bucket="3_10"} 966
telemt_desync_frames_bucket_total{bucket="gt_10"} 1217
telemt_pool_swap_total 3
telemt_pool_force_close_total 177
telemt_me_writer_removed_unexpected_total 1958
telemt_me_writer_restored_same_endpoint_total 1854
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 461606
telemt_user_connections_current{user="hello"} 1147
telemt_user_octets_from_client{user="hello"} 11721687812 (10.92 GB)
telemt_user_octets_to_client{user="hello"} 182441403988 (169.91 GB)
telemt_user_unique_ips_current{user="hello"} 316
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 18185.9 (5h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205726
telemt_connections_bad_total 860
telemt_handshake_timeouts_total 6521
telemt_upstream_connect_attempt_total 8848
telemt_upstream_connect_success_total 8828
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 8848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4237
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4590
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 912
telemt_me_reconnect_success_total 898
telemt_me_reader_eof_total 948
telemt_me_idle_close_by_peer_total 948
telemt_me_route_drop_no_conn_total 102477
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 736
telemt_desync_full_logged_total 236
telemt_desync_suppressed_total 500
telemt_desync_frames_bucket_total{bucket="1_2"} 125
telemt_desync_frames_bucket_total{bucket="3_10"} 278
telemt_desync_frames_bucket_total{bucket="gt_10"} 333
telemt_pool_swap_total 5
telemt_pool_force_close_total 196
telemt_me_writer_removed_unexpected_total 948
telemt_me_writer_restored_same_endpoint_total 898
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 189361
telemt_user_connections_current{user="hello"} 269
telemt_user_octets_from_client{user="hello"} 2124960684 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 81494855104 (75.90 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 18185.9 (5h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 411581
telemt_connections_bad_total 5288
telemt_handshake_timeouts_total 37397
telemt_upstream_connect_attempt_total 15437
telemt_upstream_connect_success_total 15366
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 15425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6929
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 209
telemt_me_reconnect_attempts_total 5332
telemt_me_reconnect_success_total 5312
telemt_me_reader_eof_total 5627
telemt_me_idle_close_by_peer_total 5627
telemt_me_route_drop_no_conn_total 195976
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 769
telemt_desync_full_logged_total 232
telemt_desync_suppressed_total 537
telemt_desync_frames_bucket_total{bucket="1_2"} 182
telemt_desync_frames_bucket_total{bucket="3_10"} 312
telemt_desync_frames_bucket_total{bucket="gt_10"} 275
telemt_pool_swap_total 2
telemt_pool_force_close_total 169
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 5631
telemt_me_writer_restored_same_endpoint_total 5307
telemt_me_writer_removed_unexpected_minus_restored_total 324
telemt_user_connections_total{user="hello"} 355691
telemt_user_connections_current{user="hello"} 763
telemt_user_octets_from_client{user="hello"} 5447539752 (5.07 GB)
telemt_user_octets_to_client{user="hello"} 113217383332 (105.44 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 17501.9 (4h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 312823
telemt_connections_bad_total 66399
telemt_handshake_timeouts_total 10289
telemt_upstream_connect_attempt_total 9470
telemt_upstream_connect_success_total 9470
telemt_upstream_connect_attempts_per_request{bucket="1"} 9470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5708
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3762
telemt_me_keepalive_timeout_total 113
telemt_me_reconnect_attempts_total 1929
telemt_me_reconnect_success_total 1915
telemt_me_reader_eof_total 1950
telemt_me_idle_close_by_peer_total 1950
telemt_me_route_drop_no_conn_total 104456
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 282
telemt_desync_full_logged_total 99
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 100
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 1950
telemt_me_writer_restored_same_endpoint_total 1915
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 201959
telemt_user_connections_current{user="hello"} 552
telemt_user_octets_from_client{user="hello"} 2392319700 (2.23 GB)
telemt_user_octets_to_client{user="hello"} 74944938168 (69.80 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 18186.5 (5h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 322377
telemt_connections_bad_total 9801
telemt_handshake_timeouts_total 2718
telemt_upstream_connect_attempt_total 8826
telemt_upstream_connect_success_total 8814
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8815
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4737
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4024
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 141
telemt_me_reconnect_attempts_total 1714
telemt_me_reconnect_success_total 1699
telemt_me_reader_eof_total 1794
telemt_me_idle_close_by_peer_total 1793
telemt_me_route_drop_no_conn_total 167140
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 74
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 562
telemt_desync_full_logged_total 203
telemt_desync_suppressed_total 359
telemt_desync_frames_bucket_total{bucket="1_2"} 258
telemt_desync_frames_bucket_total{bucket="3_10"} 158
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 4
telemt_pool_force_close_total 178
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1798
telemt_me_writer_restored_same_endpoint_total 1698
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 295883
telemt_user_connections_current{user="hello"} 505
telemt_user_octets_from_client{user="hello"} 14800127108 (13.78 GB)
telemt_user_octets_to_client{user="hello"} 160975088556 (149.92 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 106
```