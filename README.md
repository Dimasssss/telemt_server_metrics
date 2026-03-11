# Server Metrics 2026-03-11 07:12:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 60319.2 (16h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1205852
telemt_connections_bad_total 13290
telemt_handshake_timeouts_total 38859
telemt_upstream_connect_attempt_total 12619
telemt_upstream_connect_success_total 12610
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 12619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6339
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6209
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 714
telemt_me_reconnect_attempts_total 21256
telemt_me_reconnect_success_total 9573
telemt_me_reader_eof_total 10402
telemt_me_idle_close_by_peer_total 10402
telemt_me_route_drop_no_conn_total 443490
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1087734
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5281
telemt_desync_full_logged_total 1481
telemt_desync_suppressed_total 3800
telemt_desync_frames_bucket_total{bucket="1_2"} 1407
telemt_desync_frames_bucket_total{bucket="3_10"} 1978
telemt_desync_frames_bucket_total{bucket="gt_10"} 1896
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 10031
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 9567
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 458
telemt_user_connections_total{user="hello"} 1087399
telemt_user_connections_current{user="hello"} 1171
telemt_user_octets_from_client{user="hello"} 14338468844 (13.35 GB)
telemt_user_octets_to_client{user="hello"} 321238825452 (299.18 GB)
telemt_user_unique_ips_current{user="hello"} 318
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 60376.0 (16h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 465552
telemt_connections_bad_total 6026
telemt_handshake_timeouts_total 22474
telemt_upstream_connect_attempt_total 21431
telemt_upstream_connect_success_total 18516
telemt_upstream_connect_fail_total 2915
telemt_upstream_connect_attempts_per_request{bucket="1"} 21431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7937
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2915
telemt_me_keepalive_timeout_total 2039
telemt_me_reconnect_attempts_total 13359
telemt_me_reconnect_success_total 12534
telemt_me_reader_eof_total 13254
telemt_me_idle_close_by_peer_total 13252
telemt_me_route_drop_no_conn_total 207594
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 398355
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1998
telemt_desync_full_logged_total 613
telemt_desync_suppressed_total 1385
telemt_desync_frames_bucket_total{bucket="1_2"} 653
telemt_desync_frames_bucket_total{bucket="3_10"} 714
telemt_desync_frames_bucket_total{bucket="gt_10"} 631
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 12680
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 12512
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 400623
telemt_user_connections_current{user="hello"} 431
telemt_user_octets_from_client{user="hello"} 3953103230 (3.68 GB)
telemt_user_octets_to_client{user="hello"} 103695628492 (96.57 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 60375.9 (16h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 788928
telemt_connections_bad_total 6822
telemt_handshake_timeouts_total 42698
telemt_upstream_connect_attempt_total 16310
telemt_upstream_connect_success_total 16104
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 16310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7245
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_timeout_total 724
telemt_me_reconnect_attempts_total 23076
telemt_me_reconnect_success_total 12002
telemt_me_reader_eof_total 12899
telemt_me_idle_close_by_peer_total 12899
telemt_me_route_drop_no_conn_total 267274
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 705617
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2032
telemt_desync_full_logged_total 589
telemt_desync_suppressed_total 1443
telemt_desync_frames_bucket_total{bucket="1_2"} 470
telemt_desync_frames_bucket_total{bucket="3_10"} 740
telemt_desync_frames_bucket_total{bucket="gt_10"} 822
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 12498
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 11991
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 496
telemt_user_connections_total{user="hello"} 706422
telemt_user_connections_current{user="hello"} 616
telemt_user_octets_from_client{user="hello"} 8294549201 (7.72 GB)
telemt_user_octets_to_client{user="hello"} 209009997997 (194.66 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 60376.4 (16h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 604137
telemt_connections_bad_total 56580
telemt_handshake_timeouts_total 60284
telemt_upstream_connect_attempt_total 17048
telemt_upstream_connect_success_total 17048
telemt_upstream_connect_attempts_per_request{bucket="1"} 17048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9537
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7507
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 659
telemt_me_reconnect_attempts_total 15062
telemt_me_reconnect_success_total 14013
telemt_me_reader_eof_total 14880
telemt_me_idle_close_by_peer_total 14880
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 184650
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 467010
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1035
telemt_desync_full_logged_total 413
telemt_desync_suppressed_total 622
telemt_desync_frames_bucket_total{bucket="1_2"} 363
telemt_desync_frames_bucket_total{bucket="3_10"} 384
telemt_desync_frames_bucket_total{bucket="gt_10"} 288
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 14177
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 13991
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 466439
telemt_user_connections_current{user="hello"} 559
telemt_user_octets_from_client{user="hello"} 5601712932 (5.22 GB)
telemt_user_octets_to_client{user="hello"} 128100580616 (119.30 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 60375.8 (16h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 626661
telemt_connections_bad_total 5966
telemt_handshake_timeouts_total 4535
telemt_upstream_connect_attempt_total 16930
telemt_upstream_connect_success_total 16860
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 16930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8062
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 687
telemt_me_reconnect_attempts_total 17500
telemt_me_reconnect_success_total 13714
telemt_me_reader_eof_total 14491
telemt_me_idle_close_by_peer_total 14491
telemt_me_route_drop_no_conn_total 208829
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 571428
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2704
telemt_desync_full_logged_total 1021
telemt_desync_suppressed_total 1683
telemt_desync_frames_bucket_total{bucket="1_2"} 950
telemt_desync_frames_bucket_total{bucket="3_10"} 1139
telemt_desync_frames_bucket_total{bucket="gt_10"} 615
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 14009
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 13714
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 295
telemt_user_connections_total{user="hello"} 571150
telemt_user_connections_current{user="hello"} 711
telemt_user_octets_from_client{user="hello"} 9776168511 (9.10 GB)
telemt_user_octets_to_client{user="hello"} 210173743922 (195.74 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 101
```