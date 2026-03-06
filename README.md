# Server Metrics 2026-03-06 17:07:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 24346.1 (6h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 728038
telemt_connections_bad_total 11539
telemt_handshake_timeouts_total 3197
telemt_upstream_connect_attempt_total 12226
telemt_upstream_connect_success_total 12152
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 12182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5561
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 44
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 161
telemt_me_reconnect_attempts_total 2324
telemt_me_reconnect_success_total 2308
telemt_me_reader_eof_total 2414
telemt_me_idle_close_by_peer_total 2414
telemt_me_route_drop_no_conn_total 310762
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 96
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 3681
telemt_desync_full_logged_total 892
telemt_desync_suppressed_total 2789
telemt_desync_frames_bucket_total{bucket="1_2"} 881
telemt_desync_frames_bucket_total{bucket="3_10"} 1284
telemt_desync_frames_bucket_total{bucket="gt_10"} 1516
telemt_pool_swap_total 4
telemt_pool_force_close_total 234
telemt_me_writer_removed_unexpected_total 2417
telemt_me_writer_restored_same_endpoint_total 2302
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 623950
telemt_user_connections_current{user="hello"} 1100
telemt_user_octets_from_client{user="hello"} 13413105320 (12.49 GB)
telemt_user_octets_to_client{user="hello"} 226927879524 (211.34 GB)
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 24346.2 (6h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 272001
telemt_connections_bad_total 974
telemt_handshake_timeouts_total 8124
telemt_upstream_connect_attempt_total 11181
telemt_upstream_connect_success_total 11149
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 11181
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5811
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 146
telemt_me_reconnect_attempts_total 964
telemt_me_reconnect_success_total 942
telemt_me_reader_eof_total 994
telemt_me_idle_close_by_peer_total 994
telemt_me_route_drop_no_conn_total 150800
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 98
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 860
telemt_desync_full_logged_total 272
telemt_desync_suppressed_total 588
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 310
telemt_desync_frames_bucket_total{bucket="gt_10"} 397
telemt_pool_swap_total 6
telemt_pool_force_close_total 239
telemt_me_writer_removed_unexpected_total 995
telemt_me_writer_restored_same_endpoint_total 942
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 250185
telemt_user_connections_current{user="hello"} 430
telemt_user_octets_from_client{user="hello"} 2965300504 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 101126098112 (94.18 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 24346.0 (6h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 535029
telemt_connections_bad_total 5499
telemt_handshake_timeouts_total 52204
telemt_upstream_connect_attempt_total 21222
telemt_upstream_connect_success_total 21120
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 21192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9454
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 314
telemt_me_reconnect_attempts_total 7295
telemt_me_reconnect_success_total 7267
telemt_me_reader_eof_total 7718
telemt_me_idle_close_by_peer_total 7718
telemt_me_route_drop_no_conn_total 281102
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 98
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1277
telemt_desync_full_logged_total 379
telemt_desync_suppressed_total 898
telemt_desync_frames_bucket_total{bucket="1_2"} 288
telemt_desync_frames_bucket_total{bucket="3_10"} 483
telemt_desync_frames_bucket_total{bucket="gt_10"} 506
telemt_pool_swap_total 2
telemt_pool_force_close_total 169
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 7733
telemt_me_writer_restored_same_endpoint_total 7260
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 471
telemt_user_connections_total{user="hello"} 459445
telemt_user_connections_current{user="hello"} 607
telemt_user_octets_from_client{user="hello"} 6647110388 (6.19 GB)
telemt_user_octets_to_client{user="hello"} 141121047216 (131.43 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 23662.1 (6h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 511445
telemt_connections_bad_total 174943
telemt_handshake_timeouts_total 12831
telemt_upstream_connect_attempt_total 15203
telemt_upstream_connect_success_total 15201
telemt_upstream_connect_attempts_per_request{bucket="1"} 15201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6527
telemt_me_keepalive_timeout_total 201
telemt_me_reconnect_attempts_total 3902
telemt_me_reconnect_success_total 3880
telemt_me_reader_eof_total 4052
telemt_me_idle_close_by_peer_total 4052
telemt_me_route_drop_no_conn_total 163251
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 103
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 358
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 91
telemt_desync_frames_bucket_total{bucket="3_10"} 122
telemt_desync_frames_bucket_total{bucket="gt_10"} 145
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 4059
telemt_me_writer_restored_same_endpoint_total 3879
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 286684
telemt_user_connections_current{user="hello"} 541
telemt_user_octets_from_client{user="hello"} 4856503964 (4.52 GB)
telemt_user_octets_to_client{user="hello"} 99002911416 (92.20 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 24346.1 (6h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 436037
telemt_connections_bad_total 11134
telemt_handshake_timeouts_total 3914
telemt_upstream_connect_attempt_total 10732
telemt_upstream_connect_success_total 10715
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4848
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 176
telemt_me_reconnect_attempts_total 1787
telemt_me_reconnect_success_total 1767
telemt_me_reader_eof_total 1867
telemt_me_idle_close_by_peer_total 1866
telemt_me_route_drop_no_conn_total 215116
telemt_me_route_drop_channel_closed_total 5
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 94
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 849
telemt_desync_full_logged_total 300
telemt_desync_suppressed_total 549
telemt_desync_frames_bucket_total{bucket="1_2"} 378
telemt_desync_frames_bucket_total{bucket="3_10"} 247
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 7
telemt_pool_force_close_total 255
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1871
telemt_me_writer_restored_same_endpoint_total 1764
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 400791
telemt_user_connections_current{user="hello"} 637
telemt_user_octets_from_client{user="hello"} 20016356384 (18.64 GB)
telemt_user_octets_to_client{user="hello"} 202667313972 (188.75 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 99
```