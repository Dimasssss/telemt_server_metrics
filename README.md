# Server Metrics 2026-03-06 18:04:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 27743.6 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 823043
telemt_connections_bad_total 13818
telemt_handshake_timeouts_total 3563
telemt_upstream_connect_attempt_total 13807
telemt_upstream_connect_success_total 13721
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 13756
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7446
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6180
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 184
telemt_me_reconnect_attempts_total 2676
telemt_me_reconnect_success_total 2655
telemt_me_reader_eof_total 2781
telemt_me_idle_close_by_peer_total 2781
telemt_me_route_drop_no_conn_total 342153
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 110
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 4160
telemt_desync_full_logged_total 1033
telemt_desync_suppressed_total 3127
telemt_desync_frames_bucket_total{bucket="1_2"} 992
telemt_desync_frames_bucket_total{bucket="3_10"} 1486
telemt_desync_frames_bucket_total{bucket="gt_10"} 1682
telemt_pool_swap_total 5
telemt_pool_force_close_total 313
telemt_me_writer_removed_unexpected_total 2785
telemt_me_writer_restored_same_endpoint_total 2649
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 703300
telemt_user_connections_current{user="hello"} 1071
telemt_user_octets_from_client{user="hello"} 14307934924 (13.33 GB)
telemt_user_octets_to_client{user="hello"} 259727563896 (241.89 GB)
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 27743.4 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 303331
telemt_connections_bad_total 1140
telemt_handshake_timeouts_total 8628
telemt_upstream_connect_attempt_total 12547
telemt_upstream_connect_success_total 12514
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 12547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6530
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 177
telemt_me_reconnect_attempts_total 996
telemt_me_reconnect_success_total 971
telemt_me_reader_eof_total 1026
telemt_me_idle_close_by_peer_total 1026
telemt_me_route_drop_no_conn_total 161751
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 112
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 984
telemt_desync_full_logged_total 310
telemt_desync_suppressed_total 674
telemt_desync_frames_bucket_total{bucket="1_2"} 174
telemt_desync_frames_bucket_total{bucket="3_10"} 367
telemt_desync_frames_bucket_total{bucket="gt_10"} 443
telemt_pool_swap_total 7
telemt_pool_force_close_total 282
telemt_me_writer_removed_unexpected_total 1028
telemt_me_writer_restored_same_endpoint_total 971
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 279727
telemt_user_connections_current{user="hello"} 405
telemt_user_octets_from_client{user="hello"} 3430182608 (3.19 GB)
telemt_user_octets_to_client{user="hello"} 110371241060 (102.79 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 27743.4 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 590951
telemt_connections_bad_total 5666
telemt_handshake_timeouts_total 53834
telemt_upstream_connect_attempt_total 23548
telemt_upstream_connect_success_total 23432
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 23517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10448
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 348
telemt_me_reconnect_attempts_total 8004
telemt_me_reconnect_success_total 7971
telemt_me_reader_eof_total 8470
telemt_me_idle_close_by_peer_total 8470
telemt_me_route_drop_no_conn_total 312082
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 112
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1579
telemt_desync_full_logged_total 463
telemt_desync_suppressed_total 1116
telemt_desync_frames_bucket_total{bucket="1_2"} 354
telemt_desync_frames_bucket_total{bucket="3_10"} 589
telemt_desync_frames_bucket_total{bucket="gt_10"} 636
telemt_pool_swap_total 3
telemt_pool_force_close_total 237
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 8485
telemt_me_writer_restored_same_endpoint_total 7964
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 519
telemt_user_connections_total{user="hello"} 510714
telemt_user_connections_current{user="hello"} 593
telemt_user_octets_from_client{user="hello"} 7432888376 (6.92 GB)
telemt_user_octets_to_client{user="hello"} 156261156620 (145.53 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 27059.7 (7h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 577227
telemt_connections_bad_total 197405
telemt_handshake_timeouts_total 15394
telemt_upstream_connect_attempt_total 18337
telemt_upstream_connect_success_total 18335
telemt_upstream_connect_attempts_per_request{bucket="1"} 18335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7994
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 5143
telemt_me_reconnect_success_total 5117
telemt_me_reader_eof_total 5358
telemt_me_idle_close_by_peer_total 5358
telemt_me_route_drop_no_conn_total 186414
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 115
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 377
telemt_desync_full_logged_total 144
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 131
telemt_desync_frames_bucket_total{bucket="gt_10"} 148
telemt_pool_swap_total 5
telemt_pool_force_close_total 269
telemt_me_writer_removed_unexpected_total 5364
telemt_me_writer_restored_same_endpoint_total 5116
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 326301
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 5190372172 (4.83 GB)
telemt_user_octets_to_client{user="hello"} 115891409188 (107.93 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 27743.8 (7h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 517517
telemt_connections_bad_total 11236
telemt_handshake_timeouts_total 5560
telemt_upstream_connect_attempt_total 11639
telemt_upstream_connect_success_total 11619
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5360
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 190
telemt_me_reconnect_attempts_total 1799
telemt_me_reconnect_success_total 1778
telemt_me_reader_eof_total 1879
telemt_me_idle_close_by_peer_total 1878
telemt_me_route_drop_no_conn_total 237126
telemt_me_route_drop_channel_closed_total 6
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 107
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 987
telemt_desync_full_logged_total 356
telemt_desync_suppressed_total 631
telemt_desync_frames_bucket_total{bucket="1_2"} 448
telemt_desync_frames_bucket_total{bucket="3_10"} 281
telemt_desync_frames_bucket_total{bucket="gt_10"} 258
telemt_pool_swap_total 8
telemt_pool_force_close_total 297
telemt_pool_stale_pick_total 293
telemt_me_writer_removed_unexpected_total 1883
telemt_me_writer_restored_same_endpoint_total 1775
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 474386
telemt_user_connections_current{user="hello"} 552
telemt_user_octets_from_client{user="hello"} 21015486256 (19.57 GB)
telemt_user_octets_to_client{user="hello"} 221941533936 (206.70 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 96
```