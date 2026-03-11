# Server Metrics 2026-03-11 09:55:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 70098.2 (19h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1514004
telemt_connections_bad_total 22439
telemt_handshake_timeouts_total 40850
telemt_upstream_connect_attempt_total 14495
telemt_upstream_connect_success_total 14486
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 14495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7078
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 783
telemt_me_reconnect_attempts_total 22650
telemt_me_reconnect_success_total 10962
telemt_me_reader_eof_total 11873
telemt_me_idle_close_by_peer_total 11873
telemt_me_route_drop_no_conn_total 558915
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1373835
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6826
telemt_desync_full_logged_total 1888
telemt_desync_suppressed_total 4938
telemt_desync_frames_bucket_total{bucket="1_2"} 1805
telemt_desync_frames_bucket_total{bucket="3_10"} 2584
telemt_desync_frames_bucket_total{bucket="gt_10"} 2437
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 11433
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 10956
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 471
telemt_user_connections_total{user="hello"} 1372426
telemt_user_connections_current{user="hello"} 1273
telemt_user_octets_from_client{user="hello"} 18066248324 (16.83 GB)
telemt_user_octets_to_client{user="hello"} 393808456232 (366.76 GB)
telemt_user_unique_ips_current{user="hello"} 363
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 70154.8 (19h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 580466
telemt_connections_bad_total 10176
telemt_handshake_timeouts_total 32745
telemt_upstream_connect_attempt_total 23515
telemt_upstream_connect_success_total 20586
telemt_upstream_connect_fail_total 2929
telemt_upstream_connect_attempts_per_request{bucket="1"} 23515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8957
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2929
telemt_me_keepalive_timeout_total 2110
telemt_me_reconnect_attempts_total 14983
telemt_me_reconnect_success_total 14144
telemt_me_reader_eof_total 14977
telemt_me_idle_close_by_peer_total 14975
telemt_me_route_drop_no_conn_total 240352
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 492348
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2238
telemt_desync_full_logged_total 688
telemt_desync_suppressed_total 1550
telemt_desync_frames_bucket_total{bucket="1_2"} 748
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 688
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 14310
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 14122
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 494584
telemt_user_connections_current{user="hello"} 551
telemt_user_octets_from_client{user="hello"} 4798342334 (4.47 GB)
telemt_user_octets_to_client{user="hello"} 137040834004 (127.63 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 70154.9 (19h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1009950
telemt_connections_bad_total 7605
telemt_handshake_timeouts_total 98814
telemt_upstream_connect_attempt_total 18897
telemt_upstream_connect_success_total 18666
telemt_upstream_connect_fail_total 231
telemt_upstream_connect_attempts_per_request{bucket="1"} 18897
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8392
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 231
telemt_me_keepalive_timeout_total 776
telemt_me_reconnect_attempts_total 26459
telemt_me_reconnect_success_total 14091
telemt_me_reader_eof_total 15129
telemt_me_idle_close_by_peer_total 15129
telemt_me_route_drop_no_conn_total 332026
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 864235
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2482
telemt_desync_full_logged_total 731
telemt_desync_suppressed_total 1751
telemt_desync_frames_bucket_total{bucket="1_2"} 596
telemt_desync_frames_bucket_total{bucket="3_10"} 905
telemt_desync_frames_bucket_total{bucket="gt_10"} 981
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 14661
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 14080
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 570
telemt_user_connections_total{user="hello"} 865101
telemt_user_connections_current{user="hello"} 769
telemt_user_octets_from_client{user="hello"} 10223962761 (9.52 GB)
telemt_user_octets_to_client{user="hello"} 264323395125 (246.17 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 70155.1 (19h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 736266
telemt_connections_bad_total 66039
telemt_handshake_timeouts_total 70846
telemt_upstream_connect_attempt_total 19174
telemt_upstream_connect_success_total 19174
telemt_upstream_connect_attempts_per_request{bucket="1"} 19174
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8532
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 712
telemt_me_reconnect_attempts_total 16743
telemt_me_reconnect_success_total 15688
telemt_me_reader_eof_total 16660
telemt_me_idle_close_by_peer_total 16659
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 230288
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 577176
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1265
telemt_desync_full_logged_total 479
telemt_desync_suppressed_total 786
telemt_desync_frames_bucket_total{bucket="1_2"} 432
telemt_desync_frames_bucket_total{bucket="3_10"} 471
telemt_desync_frames_bucket_total{bucket="gt_10"} 362
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 15874
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 15665
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 576550
telemt_user_connections_current{user="hello"} 616
telemt_user_octets_from_client{user="hello"} 6689060320 (6.23 GB)
telemt_user_octets_to_client{user="hello"} 164754086452 (153.44 GB)
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 70154.7 (19h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 783142
telemt_connections_bad_total 6078
telemt_handshake_timeouts_total 7659
telemt_upstream_connect_attempt_total 18929
telemt_upstream_connect_success_total 18852
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 18929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8976
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 781
telemt_me_reconnect_attempts_total 19042
telemt_me_reconnect_success_total 15249
telemt_me_reader_eof_total 16122
telemt_me_idle_close_by_peer_total 16122
telemt_me_route_drop_no_conn_total 268881
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 710134
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2980
telemt_desync_full_logged_total 1127
telemt_desync_suppressed_total 1853
telemt_desync_frames_bucket_total{bucket="1_2"} 1043
telemt_desync_frames_bucket_total{bucket="3_10"} 1217
telemt_desync_frames_bucket_total{bucket="gt_10"} 720
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 15561
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 15249
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 312
telemt_user_connections_total{user="hello"} 709813
telemt_user_connections_current{user="hello"} 674
telemt_user_octets_from_client{user="hello"} 11095390563 (10.33 GB)
telemt_user_octets_to_client{user="hello"} 257087871238 (239.43 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 111
```