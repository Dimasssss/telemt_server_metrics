# Server Metrics 2026-03-04 16:24:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 69237.2 (19h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1330578
telemt_connections_bad_total 18540
telemt_handshake_timeouts_total 22917
telemt_upstream_connect_attempt_total 40420
telemt_upstream_connect_success_total 40233
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 40233
telemt_upstream_connect_attempts_per_request{bucket="2"} 73
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17989
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 456
telemt_me_reconnect_attempts_total 8637
telemt_me_reconnect_success_total 8569
telemt_me_reader_eof_total 8856
telemt_me_idle_close_by_peer_total 8855
telemt_me_route_drop_no_conn_total 517373
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 270
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2848
telemt_desync_full_logged_total 905
telemt_desync_suppressed_total 1943
telemt_desync_frames_bucket_total{bucket="1_2"} 820
telemt_desync_frames_bucket_total{bucket="3_10"} 1064
telemt_desync_frames_bucket_total{bucket="gt_10"} 964
telemt_pool_swap_total 17
telemt_pool_force_close_total 715
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8856
telemt_me_writer_restored_same_endpoint_total 8547
telemt_me_writer_removed_unexpected_minus_restored_total 309
telemt_user_connections_total{user="hello"} 1082779
telemt_user_connections_current{user="hello"} 1005
telemt_user_octets_from_client{user="hello"} 14473234480 (13.48 GB)
telemt_user_octets_to_client{user="hello"} 362482646412 (337.59 GB)
telemt_user_unique_ips_current{user="hello"} 96
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 69233.5 (19h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 505910
telemt_connections_bad_total 5066
telemt_handshake_timeouts_total 30685
telemt_upstream_connect_attempt_total 124221
telemt_upstream_connect_success_total 122467
telemt_upstream_connect_fail_total 839
telemt_upstream_connect_attempts_per_request{bucket="1"} 122461
telemt_upstream_connect_attempts_per_request{bucket="2"} 845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 839
telemt_me_keepalive_timeout_total 1634
telemt_me_reconnect_attempts_total 67709
telemt_me_reconnect_success_total 67602
telemt_me_reader_eof_total 69339
telemt_me_idle_close_by_peer_total 69338
telemt_me_route_drop_no_conn_total 207905
telemt_me_hardswap_pending_ttl_expired_total 21
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 289
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1312
telemt_desync_full_logged_total 398
telemt_desync_suppressed_total 914
telemt_desync_frames_bucket_total{bucket="1_2"} 244
telemt_desync_frames_bucket_total{bucket="3_10"} 517
telemt_desync_frames_bucket_total{bucket="gt_10"} 551
telemt_pool_swap_total 5
telemt_pool_force_close_total 379
telemt_pool_stale_pick_total 148
telemt_me_writer_removed_unexpected_total 69419
telemt_me_writer_restored_same_endpoint_total 67576
telemt_me_writer_removed_unexpected_minus_restored_total 1843
telemt_user_connections_total{user="hello"} 405696
telemt_user_connections_current{user="hello"} 445
telemt_user_octets_from_client{user="hello"} 6112925196 (5.69 GB)
telemt_user_octets_to_client{user="hello"} 127626931100 (118.86 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 69232.4 (19h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1021482
telemt_connections_bad_total 204816
telemt_handshake_timeouts_total 30343
telemt_upstream_connect_attempt_total 90296
telemt_upstream_connect_success_total 89678
telemt_upstream_connect_fail_total 299
telemt_upstream_connect_attempts_per_request{bucket="1"} 89677
telemt_upstream_connect_attempts_per_request{bucket="2"} 300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36592
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 238
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 299
telemt_me_keepalive_timeout_total 1178
telemt_me_reconnect_attempts_total 40245
telemt_me_reconnect_success_total 40138
telemt_me_reader_eof_total 42262
telemt_me_idle_close_by_peer_total 42257
telemt_me_route_drop_no_conn_total 375620
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_single_endpoint_shadow_rotate_total 283
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2135
telemt_desync_full_logged_total 708
telemt_desync_suppressed_total 1427
telemt_desync_frames_bucket_total{bucket="1_2"} 636
telemt_desync_frames_bucket_total{bucket="3_10"} 694
telemt_desync_frames_bucket_total{bucket="gt_10"} 805
telemt_pool_swap_total 8
telemt_pool_force_close_total 453
telemt_me_writer_removed_unexpected_total 42275
telemt_me_writer_restored_same_endpoint_total 40116
telemt_me_writer_removed_unexpected_minus_restored_total 2159
telemt_user_connections_total{user="hello"} 738970
telemt_user_connections_current{user="hello"} 708
telemt_user_octets_from_client{user="hello"} 14513968584 (13.52 GB)
telemt_user_octets_to_client{user="hello"} 253650649256 (236.23 GB)
telemt_user_unique_ips_current{user="hello"} 78
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 15909.6 (4h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 261157
telemt_connections_bad_total 31847
telemt_handshake_timeouts_total 6471
telemt_upstream_connect_attempt_total 6342
telemt_upstream_connect_success_total 6342
telemt_upstream_connect_attempts_per_request{bucket="1"} 6342
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2776
telemt_me_keepalive_timeout_total 77
telemt_me_reconnect_attempts_total 873
telemt_me_reconnect_success_total 880
telemt_me_reader_eof_total 890
telemt_me_idle_close_by_peer_total 890
telemt_me_route_drop_no_conn_total 86508
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 244
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 152
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 5
telemt_pool_force_close_total 189
telemt_me_writer_removed_unexpected_total 890
telemt_me_writer_restored_same_endpoint_total 859
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 213745
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 2773130464 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 81536828860 (75.94 GB)
telemt_user_unique_ips_current{user="hello"} 51
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 16268.9 (4h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 278292
telemt_connections_bad_total 2640
telemt_handshake_timeouts_total 4057
telemt_upstream_connect_attempt_total 7849
telemt_upstream_connect_success_total 7809
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 7809
telemt_upstream_connect_attempts_per_request{bucket="2"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3287
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 113
telemt_me_reconnect_attempts_total 1337
telemt_me_reconnect_success_total 1342
telemt_me_reader_eof_total 1369
telemt_me_idle_close_by_peer_total 1369
telemt_me_route_drop_no_conn_total 108034
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 65
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 537
telemt_desync_full_logged_total 211
telemt_desync_suppressed_total 326
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 235
telemt_desync_frames_bucket_total{bucket="gt_10"} 222
telemt_pool_swap_total 4
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 1369
telemt_me_writer_restored_same_endpoint_total 1321
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 239661
telemt_user_connections_current{user="hello"} 537
telemt_user_octets_from_client{user="hello"} 3955497084 (3.68 GB)
telemt_user_octets_to_client{user="hello"} 71395195712 (66.49 GB)
telemt_user_unique_ips_current{user="hello"} 52
```