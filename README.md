# Server Metrics 2026-03-11 07:27:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 61235.9 (17h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1228930
telemt_connections_bad_total 13655
telemt_handshake_timeouts_total 39028
telemt_upstream_connect_attempt_total 12756
telemt_upstream_connect_success_total 12747
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 12756
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6417
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6268
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 716
telemt_me_reconnect_attempts_total 21348
telemt_me_reconnect_success_total 9665
telemt_me_reader_eof_total 10502
telemt_me_idle_close_by_peer_total 10502
telemt_me_route_drop_no_conn_total 453303
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1109577
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5426
telemt_desync_full_logged_total 1511
telemt_desync_suppressed_total 3915
telemt_desync_frames_bucket_total{bucket="1_2"} 1442
telemt_desync_frames_bucket_total{bucket="3_10"} 2035
telemt_desync_frames_bucket_total{bucket="gt_10"} 1949
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 10125
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 9659
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 460
telemt_user_connections_total{user="hello"} 1109240
telemt_user_connections_current{user="hello"} 1071
telemt_user_octets_from_client{user="hello"} 14698133508 (13.69 GB)
telemt_user_octets_to_client{user="hello"} 328012797024 (305.49 GB)
telemt_user_unique_ips_current{user="hello"} 320
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 61292.5 (17h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 475483
telemt_connections_bad_total 6929
telemt_handshake_timeouts_total 22767
telemt_upstream_connect_attempt_total 21639
telemt_upstream_connect_success_total 18722
telemt_upstream_connect_fail_total 2917
telemt_upstream_connect_attempts_per_request{bucket="1"} 21639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8043
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2917
telemt_me_keepalive_timeout_total 2043
telemt_me_reconnect_attempts_total 13516
telemt_me_reconnect_success_total 12690
telemt_me_reader_eof_total 13420
telemt_me_idle_close_by_peer_total 13418
telemt_me_route_drop_no_conn_total 209551
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 406393
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2029
telemt_desync_full_logged_total 623
telemt_desync_suppressed_total 1406
telemt_desync_frames_bucket_total{bucket="1_2"} 659
telemt_desync_frames_bucket_total{bucket="3_10"} 730
telemt_desync_frames_bucket_total{bucket="gt_10"} 640
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12836
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 12668
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 408661
telemt_user_connections_current{user="hello"} 370
telemt_user_octets_from_client{user="hello"} 4013762898 (3.74 GB)
telemt_user_octets_to_client{user="hello"} 107533178460 (100.15 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 61292.3 (17h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 803237
telemt_connections_bad_total 6868
telemt_handshake_timeouts_total 43470
telemt_upstream_connect_attempt_total 16599
telemt_upstream_connect_success_total 16393
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 16599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7393
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_timeout_total 733
telemt_me_reconnect_attempts_total 24588
telemt_me_reconnect_success_total 12233
telemt_me_reader_eof_total 13174
telemt_me_idle_close_by_peer_total 13174
telemt_me_route_drop_no_conn_total 272325
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 718417
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2097
telemt_desync_full_logged_total 613
telemt_desync_suppressed_total 1484
telemt_desync_frames_bucket_total{bucket="1_2"} 486
telemt_desync_frames_bucket_total{bucket="3_10"} 766
telemt_desync_frames_bucket_total{bucket="gt_10"} 845
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 12773
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 12222
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 540
telemt_user_connections_total{user="hello"} 719217
telemt_user_connections_current{user="hello"} 582
telemt_user_octets_from_client{user="hello"} 8451320217 (7.87 GB)
telemt_user_octets_to_client{user="hello"} 212607836617 (198.01 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 61292.8 (17h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 614488
telemt_connections_bad_total 57423
telemt_handshake_timeouts_total 60935
telemt_upstream_connect_attempt_total 17262
telemt_upstream_connect_success_total 17262
telemt_upstream_connect_attempts_per_request{bucket="1"} 17262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7608
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 661
telemt_me_reconnect_attempts_total 15222
telemt_me_reconnect_success_total 14173
telemt_me_reader_eof_total 15050
telemt_me_idle_close_by_peer_total 15050
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 187996
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 475709
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1072
telemt_desync_full_logged_total 422
telemt_desync_suppressed_total 650
telemt_desync_frames_bucket_total{bucket="1_2"} 368
telemt_desync_frames_bucket_total{bucket="3_10"} 404
telemt_desync_frames_bucket_total{bucket="gt_10"} 300
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 14339
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 14151
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 475129
telemt_user_connections_current{user="hello"} 481
telemt_user_octets_from_client{user="hello"} 5672789476 (5.28 GB)
telemt_user_octets_to_client{user="hello"} 130277864112 (121.33 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 61292.5 (17h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 640770
telemt_connections_bad_total 5968
telemt_handshake_timeouts_total 4634
telemt_upstream_connect_attempt_total 17109
telemt_upstream_connect_success_total 17039
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 17109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8150
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 688
telemt_me_reconnect_attempts_total 17628
telemt_me_reconnect_success_total 13842
telemt_me_reader_eof_total 14625
telemt_me_idle_close_by_peer_total 14625
telemt_me_route_drop_no_conn_total 213454
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 583761
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2734
telemt_desync_full_logged_total 1032
telemt_desync_suppressed_total 1702
telemt_desync_frames_bucket_total{bucket="1_2"} 961
telemt_desync_frames_bucket_total{bucket="3_10"} 1146
telemt_desync_frames_bucket_total{bucket="gt_10"} 627
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 14137
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 13842
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 295
telemt_user_connections_total{user="hello"} 583475
telemt_user_connections_current{user="hello"} 707
telemt_user_octets_from_client{user="hello"} 9950630731 (9.27 GB)
telemt_user_octets_to_client{user="hello"} 214308145214 (199.59 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 94
```