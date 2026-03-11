# Server Metrics 2026-03-11 16:03:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 92156.8 (25h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2286593
telemt_connections_bad_total 40292
telemt_handshake_timeouts_total 53523
telemt_upstream_connect_attempt_total 19301
telemt_upstream_connect_success_total 19289
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 19301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9708
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9487
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 4959
telemt_me_reconnect_attempts_total 32483
telemt_me_reconnect_success_total 14610
telemt_me_reader_eof_total 15848
telemt_me_idle_close_by_peer_total 15848
telemt_me_route_drop_no_conn_total 847598
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2090751
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10874
telemt_desync_full_logged_total 2959
telemt_desync_suppressed_total 7915
telemt_desync_frames_bucket_total{bucket="1_2"} 2693
telemt_desync_frames_bucket_total{bucket="3_10"} 4194
telemt_desync_frames_bucket_total{bucket="gt_10"} 3987
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 15330
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 14604
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 720
telemt_user_connections_total{user="hello"} 2089191
telemt_user_connections_current{user="hello"} 1390
telemt_user_octets_from_client{user="hello"} 28071667956 (26.14 GB)
telemt_user_octets_to_client{user="hello"} 590545159296 (549.99 GB)
telemt_user_unique_ips_current{user="hello"} 384
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 92213.5 (25h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 848082
telemt_connections_bad_total 14418
telemt_handshake_timeouts_total 59756
telemt_upstream_connect_attempt_total 29191
telemt_upstream_connect_success_total 26233
telemt_upstream_connect_fail_total 2958
telemt_upstream_connect_attempts_per_request{bucket="1"} 29191
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12229
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11756
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2958
telemt_me_keepalive_timeout_total 2593
telemt_me_reconnect_attempts_total 20740
telemt_me_reconnect_success_total 18647
telemt_me_reader_eof_total 19744
telemt_me_idle_close_by_peer_total 19741
telemt_me_route_drop_no_conn_total 330507
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 719051
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2935
telemt_desync_full_logged_total 936
telemt_desync_suppressed_total 1999
telemt_desync_frames_bucket_total{bucket="1_2"} 907
telemt_desync_frames_bucket_total{bucket="3_10"} 1054
telemt_desync_frames_bucket_total{bucket="gt_10"} 974
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 18914
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 18624
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 721511
telemt_user_connections_current{user="hello"} 524
telemt_user_octets_from_client{user="hello"} 8304465526 (7.73 GB)
telemt_user_octets_to_client{user="hello"} 204560366828 (190.51 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 92213.4 (25h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1464968
telemt_connections_bad_total 8688
telemt_handshake_timeouts_total 124855
telemt_upstream_connect_attempt_total 24058
telemt_upstream_connect_success_total 23757
telemt_upstream_connect_fail_total 301
telemt_upstream_connect_attempts_per_request{bucket="1"} 24058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12826
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10806
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 301
telemt_me_keepalive_timeout_total 1655
telemt_me_reconnect_attempts_total 40400
telemt_me_reconnect_success_total 18024
telemt_me_reader_eof_total 19529
telemt_me_idle_close_by_peer_total 19529
telemt_me_route_drop_no_conn_total 535145
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1278439
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3365
telemt_desync_full_logged_total 998
telemt_desync_suppressed_total 2367
telemt_desync_frames_bucket_total{bucket="1_2"} 830
telemt_desync_frames_bucket_total{bucket="3_10"} 1274
telemt_desync_frames_bucket_total{bucket="gt_10"} 1261
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 18968
telemt_me_refill_failed_total 694
telemt_me_writer_restored_same_endpoint_total 18012
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 944
telemt_user_connections_total{user="hello"} 1278148
telemt_user_connections_current{user="hello"} 887
telemt_user_octets_from_client{user="hello"} 15373791713 (14.32 GB)
telemt_user_octets_to_client{user="hello"} 386689638269 (360.13 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 92213.9 (25h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1054744
telemt_connections_bad_total 77972
telemt_handshake_timeouts_total 102821
telemt_upstream_connect_attempt_total 24796
telemt_upstream_connect_success_total 24796
telemt_upstream_connect_attempts_per_request{bucket="1"} 24796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11241
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1042
telemt_me_reconnect_attempts_total 21265
telemt_me_reconnect_success_total 20190
telemt_me_reader_eof_total 21407
telemt_me_idle_close_by_peer_total 21406
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 345574
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 844449
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 30
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1756
telemt_desync_full_logged_total 675
telemt_desync_suppressed_total 1081
telemt_desync_frames_bucket_total{bucket="1_2"} 635
telemt_desync_frames_bucket_total{bucket="3_10"} 613
telemt_desync_frames_bucket_total{bucket="gt_10"} 508
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 20435
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 20160
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 843767
telemt_user_connections_current{user="hello"} 652
telemt_user_octets_from_client{user="hello"} 10100176184 (9.41 GB)
telemt_user_octets_to_client{user="hello"} 249324973880 (232.20 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 92213.5 (25h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1165443
telemt_connections_bad_total 6940
telemt_handshake_timeouts_total 11671
telemt_upstream_connect_attempt_total 25121
telemt_upstream_connect_success_total 25009
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 25121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12035
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 200
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 2032
telemt_me_reconnect_attempts_total 24347
telemt_me_reconnect_success_total 20253
telemt_me_reader_eof_total 21334
telemt_me_idle_close_by_peer_total 21334
telemt_me_route_drop_no_conn_total 415841
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1060942
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4113
telemt_desync_full_logged_total 1477
telemt_desync_suppressed_total 2636
telemt_desync_frames_bucket_total{bucket="1_2"} 1371
telemt_desync_frames_bucket_total{bucket="3_10"} 1539
telemt_desync_frames_bucket_total{bucket="gt_10"} 1203
telemt_pool_swap_total 60
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20643
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 20253
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 390
telemt_user_connections_total{user="hello"} 1060646
telemt_user_connections_current{user="hello"} 758
telemt_user_octets_from_client{user="hello"} 20085327887 (18.71 GB)
telemt_user_octets_to_client{user="hello"} 369892470418 (344.49 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 114
```