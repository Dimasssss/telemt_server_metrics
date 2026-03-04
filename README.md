# Server Metrics 2026-03-04 16:45:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 70466.1 (19h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1364716
telemt_connections_bad_total 19416
telemt_handshake_timeouts_total 23126
telemt_upstream_connect_attempt_total 41723
telemt_upstream_connect_success_total 41536
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 41536
telemt_upstream_connect_attempts_per_request{bucket="2"} 73
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18646
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 49
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 478
telemt_me_reconnect_attempts_total 9215
telemt_me_reconnect_success_total 9144
telemt_me_reader_eof_total 9468
telemt_me_idle_close_by_peer_total 9467
telemt_me_route_drop_no_conn_total 541387
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_shadow_rotate_total 274
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2977
telemt_desync_full_logged_total 942
telemt_desync_suppressed_total 2035
telemt_desync_frames_bucket_total{bucket="1_2"} 854
telemt_desync_frames_bucket_total{bucket="3_10"} 1110
telemt_desync_frames_bucket_total{bucket="gt_10"} 1013
telemt_pool_swap_total 18
telemt_pool_force_close_total 792
telemt_pool_stale_pick_total 112
telemt_me_writer_removed_unexpected_total 9469
telemt_me_writer_restored_same_endpoint_total 9122
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 1114397
telemt_user_connections_current{user="hello"} 936
telemt_user_octets_from_client{user="hello"} 14743355300 (13.73 GB)
telemt_user_octets_to_client{user="hello"} 372457591184 (346.88 GB)
telemt_user_unique_ips_current{user="hello"} 156
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 70462.7 (19h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 521116
telemt_connections_bad_total 6222
telemt_handshake_timeouts_total 30805
telemt_upstream_connect_attempt_total 124823
telemt_upstream_connect_success_total 122998
telemt_upstream_connect_fail_total 874
telemt_upstream_connect_attempts_per_request{bucket="1"} 122992
telemt_upstream_connect_attempts_per_request{bucket="2"} 880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43465
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 874
telemt_me_keepalive_timeout_total 1643
telemt_me_reconnect_attempts_total 67759
telemt_me_reconnect_success_total 67652
telemt_me_reader_eof_total 69391
telemt_me_idle_close_by_peer_total 69390
telemt_me_route_drop_no_conn_total 219962
telemt_me_hardswap_pending_ttl_expired_total 21
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 294
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1330
telemt_desync_full_logged_total 408
telemt_desync_suppressed_total 922
telemt_desync_frames_bucket_total{bucket="1_2"} 248
telemt_desync_frames_bucket_total{bucket="3_10"} 522
telemt_desync_frames_bucket_total{bucket="gt_10"} 560
telemt_pool_swap_total 5
telemt_pool_force_close_total 379
telemt_pool_stale_pick_total 184
telemt_me_writer_removed_unexpected_total 69471
telemt_me_writer_restored_same_endpoint_total 67626
telemt_me_writer_removed_unexpected_minus_restored_total 1845
telemt_user_connections_total{user="hello"} 419130
telemt_user_connections_current{user="hello"} 468
telemt_user_octets_from_client{user="hello"} 6182090756 (5.76 GB)
telemt_user_octets_to_client{user="hello"} 131836212192 (122.78 GB)
telemt_user_unique_ips_current{user="hello"} 40
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 70461.4 (19h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1047971
telemt_connections_bad_total 208557
telemt_handshake_timeouts_total 30412
telemt_upstream_connect_attempt_total 90973
telemt_upstream_connect_success_total 90340
telemt_upstream_connect_fail_total 306
telemt_upstream_connect_attempts_per_request{bucket="1"} 90339
telemt_upstream_connect_attempts_per_request{bucket="2"} 307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36845
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 306
telemt_me_keepalive_timeout_total 1186
telemt_me_reconnect_attempts_total 40269
telemt_me_reconnect_success_total 40161
telemt_me_reader_eof_total 42285
telemt_me_idle_close_by_peer_total 42280
telemt_me_route_drop_no_conn_total 388669
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_single_endpoint_shadow_rotate_total 291
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2190
telemt_desync_full_logged_total 728
telemt_desync_suppressed_total 1462
telemt_desync_frames_bucket_total{bucket="1_2"} 643
telemt_desync_frames_bucket_total{bucket="3_10"} 716
telemt_desync_frames_bucket_total{bucket="gt_10"} 831
telemt_pool_swap_total 8
telemt_pool_force_close_total 453
telemt_me_writer_removed_unexpected_total 42298
telemt_me_writer_restored_same_endpoint_total 40139
telemt_me_writer_removed_unexpected_minus_restored_total 2159
telemt_user_connections_total{user="hello"} 759511
telemt_user_connections_current{user="hello"} 613
telemt_user_octets_from_client{user="hello"} 14677099232 (13.67 GB)
telemt_user_octets_to_client{user="hello"} 261803609480 (243.82 GB)
telemt_user_unique_ips_current{user="hello"} 68
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 17138.7 (4h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 281258
telemt_connections_bad_total 34059
telemt_handshake_timeouts_total 6614
telemt_upstream_connect_attempt_total 6706
telemt_upstream_connect_success_total 6706
telemt_upstream_connect_attempts_per_request{bucket="1"} 6706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2953
telemt_me_keepalive_timeout_total 77
telemt_me_reconnect_attempts_total 879
telemt_me_reconnect_success_total 886
telemt_me_reader_eof_total 896
telemt_me_idle_close_by_peer_total 896
telemt_me_route_drop_no_conn_total 94307
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 300
telemt_desync_full_logged_total 117
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 120
telemt_pool_swap_total 5
telemt_pool_force_close_total 189
telemt_me_writer_removed_unexpected_total 896
telemt_me_writer_restored_same_endpoint_total 865
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 230844
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 2911061880 (2.71 GB)
telemt_user_octets_to_client{user="hello"} 86012912564 (80.11 GB)
telemt_user_unique_ips_current{user="hello"} 39
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 17498.2 (4h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 298419
telemt_connections_bad_total 3077
telemt_handshake_timeouts_total 4122
telemt_upstream_connect_attempt_total 8515
telemt_upstream_connect_success_total 8472
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 8472
telemt_upstream_connect_attempts_per_request{bucket="2"} 21
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3553
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 126
telemt_me_reconnect_attempts_total 1381
telemt_me_reconnect_success_total 1385
telemt_me_reader_eof_total 1412
telemt_me_idle_close_by_peer_total 1412
telemt_me_route_drop_no_conn_total 118571
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 72
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 566
telemt_desync_full_logged_total 219
telemt_desync_suppressed_total 347
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 232
telemt_pool_swap_total 4
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 1412
telemt_me_writer_restored_same_endpoint_total 1364
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 258393
telemt_user_connections_current{user="hello"} 658
telemt_user_octets_from_client{user="hello"} 4256175920 (3.96 GB)
telemt_user_octets_to_client{user="hello"} 76955968492 (71.67 GB)
telemt_user_unique_ips_current{user="hello"} 67
```