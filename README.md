# Server Metrics 2026-03-11 05:51:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 55440.8 (15h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1083663
telemt_connections_bad_total 13229
telemt_handshake_timeouts_total 37852
telemt_upstream_connect_attempt_total 11791
telemt_upstream_connect_success_total 11782
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 11791
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5806
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 551
telemt_me_reconnect_attempts_total 20644
telemt_me_reconnect_success_total 8964
telemt_me_reader_eof_total 9755
telemt_me_idle_close_by_peer_total 9755
telemt_me_route_drop_no_conn_total 398771
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 972402
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4480
telemt_desync_full_logged_total 1269
telemt_desync_suppressed_total 3211
telemt_desync_frames_bucket_total{bucket="1_2"} 1238
telemt_desync_frames_bucket_total{bucket="3_10"} 1687
telemt_desync_frames_bucket_total{bucket="gt_10"} 1555
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 9411
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 8958
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 447
telemt_user_connections_total{user="hello"} 972105
telemt_user_connections_current{user="hello"} 872
telemt_user_octets_from_client{user="hello"} 13124611960 (12.22 GB)
telemt_user_octets_to_client{user="hello"} 283356979192 (263.90 GB)
telemt_user_unique_ips_current{user="hello"} 261
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 55497.5 (15h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 418135
telemt_connections_bad_total 3505
telemt_handshake_timeouts_total 19858
telemt_upstream_connect_attempt_total 20393
telemt_upstream_connect_success_total 17486
telemt_upstream_connect_fail_total 2907
telemt_upstream_connect_attempts_per_request{bucket="1"} 20393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7426
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2907
telemt_me_keepalive_timeout_total 1793
telemt_me_reconnect_attempts_total 12577
telemt_me_reconnect_success_total 11754
telemt_me_reader_eof_total 12420
telemt_me_idle_close_by_peer_total 12418
telemt_me_route_drop_no_conn_total 194350
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 359045
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1877
telemt_desync_full_logged_total 563
telemt_desync_suppressed_total 1314
telemt_desync_frames_bucket_total{bucket="1_2"} 594
telemt_desync_frames_bucket_total{bucket="3_10"} 672
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 11889
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 11733
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 361316
telemt_user_connections_current{user="hello"} 294
telemt_user_octets_from_client{user="hello"} 3630847006 (3.38 GB)
telemt_user_octets_to_client{user="hello"} 88661900940 (82.57 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 55497.3 (15h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 714174
telemt_connections_bad_total 6050
telemt_handshake_timeouts_total 39049
telemt_upstream_connect_attempt_total 15020
telemt_upstream_connect_success_total 14820
telemt_upstream_connect_fail_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 15020
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6678
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 200
telemt_me_keepalive_timeout_total 578
telemt_me_reconnect_attempts_total 22036
telemt_me_reconnect_success_total 10963
telemt_me_reader_eof_total 11826
telemt_me_idle_close_by_peer_total 11826
telemt_me_route_drop_no_conn_total 240281
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 638058
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1815
telemt_desync_full_logged_total 527
telemt_desync_suppressed_total 1288
telemt_desync_frames_bucket_total{bucket="1_2"} 413
telemt_desync_frames_bucket_total{bucket="3_10"} 654
telemt_desync_frames_bucket_total{bucket="gt_10"} 748
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 11452
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 10952
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 489
telemt_user_connections_total{user="hello"} 638912
telemt_user_connections_current{user="hello"} 570
telemt_user_octets_from_client{user="hello"} 7692028785 (7.16 GB)
telemt_user_octets_to_client{user="hello"} 189426691737 (176.42 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 55497.6 (15h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 543716
telemt_connections_bad_total 52112
telemt_handshake_timeouts_total 56704
telemt_upstream_connect_attempt_total 15955
telemt_upstream_connect_success_total 15955
telemt_upstream_connect_attempts_per_request{bucket="1"} 15955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7007
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 501
telemt_me_reconnect_attempts_total 14217
telemt_me_reconnect_success_total 13173
telemt_me_reader_eof_total 13982
telemt_me_idle_close_by_peer_total 13982
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 160692
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 420125
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 894
telemt_desync_full_logged_total 369
telemt_desync_suppressed_total 525
telemt_desync_frames_bucket_total{bucket="1_2"} 329
telemt_desync_frames_bucket_total{bucket="3_10"} 330
telemt_desync_frames_bucket_total{bucket="gt_10"} 235
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 13324
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 13151
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 419703
telemt_user_connections_current{user="hello"} 318
telemt_user_octets_from_client{user="hello"} 5093223676 (4.74 GB)
telemt_user_octets_to_client{user="hello"} 115288514124 (107.37 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 55497.2 (15h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 567220
telemt_connections_bad_total 5958
telemt_handshake_timeouts_total 3852
telemt_upstream_connect_attempt_total 15885
telemt_upstream_connect_success_total 15818
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 15885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7606
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 565
telemt_me_reconnect_attempts_total 16777
telemt_me_reconnect_success_total 12994
telemt_me_reader_eof_total 13716
telemt_me_idle_close_by_peer_total 13716
telemt_me_route_drop_no_conn_total 185494
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 518360
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2517
telemt_desync_full_logged_total 975
telemt_desync_suppressed_total 1542
telemt_desync_frames_bucket_total{bucket="1_2"} 913
telemt_desync_frames_bucket_total{bucket="3_10"} 1069
telemt_desync_frames_bucket_total{bucket="gt_10"} 535
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 13275
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 12994
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 518001
telemt_user_connections_current{user="hello"} 471
telemt_user_octets_from_client{user="hello"} 9216532372 (8.58 GB)
telemt_user_octets_to_client{user="hello"} 180871529816 (168.45 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 69
```