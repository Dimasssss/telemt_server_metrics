# Server Metrics 2026-03-06 22:41:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 16435.5 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 259723
telemt_connections_bad_total 2243
telemt_handshake_timeouts_total 9168
telemt_upstream_connect_attempt_total 28289
telemt_upstream_connect_success_total 27994
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 28157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18699
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 67
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_keepalive_timeout_total 1128
telemt_me_reconnect_attempts_total 9384
telemt_me_reconnect_success_total 9255
telemt_me_reader_eof_total 11707
telemt_me_idle_close_by_peer_total 11707
telemt_me_route_drop_no_conn_total 99986
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 139
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 830
telemt_desync_full_logged_total 243
telemt_desync_suppressed_total 587
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 332
telemt_desync_frames_bucket_total{bucket="gt_10"} 257
telemt_pool_swap_total 5
telemt_pool_force_close_total 320
telemt_pool_stale_pick_total 173
telemt_me_writer_removed_unexpected_total 11815
telemt_me_writer_restored_same_endpoint_total 9244
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 1511
telemt_me_writer_removed_unexpected_minus_restored_total 2566
telemt_user_connections_total{user="hello"} 234423
telemt_user_connections_current{user="hello"} 500
telemt_user_octets_from_client{user="hello"} 3726923080 (3.47 GB)
telemt_user_octets_to_client{user="hello"} 102023970636 (95.02 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 16435.2 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106206
telemt_connections_bad_total 99
telemt_handshake_timeouts_total 9390
telemt_upstream_connect_attempt_total 35230
telemt_upstream_connect_success_total 35229
telemt_upstream_connect_attempts_per_request{bucket="1"} 35229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23590
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 553
telemt_me_reconnect_attempts_total 13987
telemt_me_reconnect_success_total 13962
telemt_me_reader_eof_total 16618
telemt_me_idle_close_by_peer_total 16615
telemt_me_route_drop_no_conn_total 37442
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 143
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 674
telemt_desync_full_logged_total 181
telemt_desync_suppressed_total 493
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 317
telemt_desync_frames_bucket_total{bucket="gt_10"} 246
telemt_pool_swap_total 8
telemt_pool_force_close_total 333
telemt_pool_stale_pick_total 37
telemt_me_writer_removed_unexpected_total 16618
telemt_me_writer_restored_same_endpoint_total 13960
telemt_me_async_recovery_trigger_total 1500
telemt_me_writer_removed_unexpected_minus_restored_total 2658
telemt_user_connections_total{user="hello"} 91132
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 1372964972 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 33475259980 (31.18 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 16434.8 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202513
telemt_connections_bad_total 864
telemt_handshake_timeouts_total 3247
telemt_upstream_connect_attempt_total 28953
telemt_upstream_connect_success_total 28800
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 28844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15510
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 1120
telemt_me_reconnect_attempts_total 10345
telemt_me_reconnect_success_total 10311
telemt_me_reader_eof_total 11475
telemt_me_idle_close_by_peer_total 11472
telemt_me_route_drop_no_conn_total 76604
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 139
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 911
telemt_desync_full_logged_total 226
telemt_desync_suppressed_total 685
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 368
telemt_desync_frames_bucket_total{bucket="gt_10"} 372
telemt_pool_swap_total 9
telemt_pool_force_close_total 276
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 11582
telemt_me_writer_restored_same_endpoint_total 10304
telemt_me_async_recovery_trigger_total 4376
telemt_me_writer_removed_unexpected_minus_restored_total 1278
telemt_user_connections_total{user="hello"} 187956
telemt_user_connections_current{user="hello"} 236
telemt_user_octets_from_client{user="hello"} 13392821932 (12.47 GB)
telemt_user_octets_to_client{user="hello"} 56907025916 (53.00 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 16435.0 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201301
telemt_connections_bad_total 54746
telemt_handshake_timeouts_total 15957
telemt_upstream_connect_attempt_total 27850
telemt_upstream_connect_success_total 27776
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 27803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15773
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 545
telemt_me_reconnect_attempts_total 8983
telemt_me_reconnect_success_total 8964
telemt_me_reader_eof_total 12035
telemt_me_idle_close_by_peer_total 12034
telemt_me_route_drop_no_conn_total 52057
telemt_me_single_endpoint_shadow_rotate_total 140
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 9
telemt_pool_force_close_total 332
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 12040
telemt_me_writer_restored_same_endpoint_total 8959
telemt_me_writer_removed_unexpected_minus_restored_total 3081
telemt_user_connections_total{user="hello"} 127183
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 1624400956 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 40483264408 (37.70 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 16433.9 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175408
telemt_connections_bad_total 459
telemt_handshake_timeouts_total 1358
telemt_upstream_connect_attempt_total 25102
telemt_upstream_connect_success_total 24968
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 24987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14650
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 174
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 824
telemt_me_reconnect_attempts_total 7430
telemt_me_reconnect_success_total 7401
telemt_me_reader_eof_total 9937
telemt_me_idle_close_by_peer_total 9936
telemt_me_route_drop_no_conn_total 60439
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 136
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 733
telemt_desync_full_logged_total 184
telemt_desync_suppressed_total 549
telemt_desync_frames_bucket_total{bucket="1_2"} 259
telemt_desync_frames_bucket_total{bucket="3_10"} 235
telemt_desync_frames_bucket_total{bucket="gt_10"} 239
telemt_pool_swap_total 8
telemt_pool_force_close_total 319
telemt_pool_stale_pick_total 203
telemt_me_writer_removed_unexpected_total 10002
telemt_me_writer_restored_same_endpoint_total 7399
telemt_me_writer_removed_unexpected_minus_restored_total 2603
telemt_user_connections_total{user="hello"} 160562
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 10011105572 (9.32 GB)
telemt_user_octets_to_client{user="hello"} 54097438624 (50.38 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 20
```