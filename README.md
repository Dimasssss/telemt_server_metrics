# Server Metrics 2026-03-15 12:43:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 52118.4 (14h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1480933
telemt_connections_bad_total 86346
telemt_handshake_timeouts_total 12759
telemt_upstream_connect_attempt_total 10333
telemt_upstream_connect_success_total 10285
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 10333
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4804
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 12564
telemt_me_reconnect_success_total 7685
telemt_me_reader_eof_total 8248
telemt_me_idle_close_by_peer_total 8248
telemt_me_route_drop_no_conn_total 496839
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1244225
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4672
telemt_desync_full_logged_total 1315
telemt_desync_suppressed_total 3357
telemt_desync_frames_bucket_total{bucket="1_2"} 1151
telemt_desync_frames_bucket_total{bucket="3_10"} 1838
telemt_desync_frames_bucket_total{bucket="gt_10"} 1683
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 7954
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 7674
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 269
telemt_user_connections_total{user="hello"} 1243888
telemt_user_connections_current{user="hello"} 2194
telemt_user_octets_from_client{user="hello"} 17497272784 (16.30 GB)
telemt_user_octets_to_client{user="hello"} 496718784176 (462.61 GB)
telemt_user_unique_ips_current{user="hello"} 618
telemt_user_unique_ips_recent_window{user="hello"} 300
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 52119.3 (14h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 595196
telemt_connections_bad_total 30033
telemt_handshake_timeouts_total 38822
telemt_upstream_connect_attempt_total 13492
telemt_upstream_connect_success_total 13424
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 13492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6058
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 10565
telemt_me_reconnect_success_total 10489
telemt_me_reader_eof_total 11089
telemt_me_idle_close_by_peer_total 11089
telemt_me_route_drop_no_conn_total 150319
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 456621
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1795
telemt_desync_full_logged_total 627
telemt_desync_suppressed_total 1168
telemt_desync_frames_bucket_total{bucket="1_2"} 677
telemt_desync_frames_bucket_total{bucket="3_10"} 663
telemt_desync_frames_bucket_total{bucket="gt_10"} 455
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 10609
telemt_me_writer_restored_same_endpoint_total 10477
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 456886
telemt_user_connections_current{user="hello"} 501
telemt_user_octets_from_client{user="hello"} 6469847651 (6.03 GB)
telemt_user_octets_to_client{user="hello"} 169115805488 (157.50 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 52119.3 (14h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1197933
telemt_connections_bad_total 39685
telemt_handshake_timeouts_total 121969
telemt_upstream_connect_attempt_total 11483
telemt_upstream_connect_success_total 11427
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 11483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5470
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_reconnect_attempts_total 10059
telemt_me_reconnect_success_total 8814
telemt_me_reader_eof_total 9352
telemt_me_idle_close_by_peer_total 9352
telemt_me_route_drop_no_conn_total 359936
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 797743
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2057
telemt_desync_full_logged_total 737
telemt_desync_suppressed_total 1320
telemt_desync_frames_bucket_total{bucket="1_2"} 469
telemt_desync_frames_bucket_total{bucket="3_10"} 765
telemt_desync_frames_bucket_total{bucket="gt_10"} 823
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 8967
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 8795
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 794234
telemt_user_connections_current{user="hello"} 1357
telemt_user_octets_from_client{user="hello"} 11648331416 (10.85 GB)
telemt_user_octets_to_client{user="hello"} 297338938812 (276.92 GB)
telemt_user_unique_ips_current{user="hello"} 402
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 52119.1 (14h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 592893
telemt_connections_bad_total 66624
telemt_handshake_timeouts_total 33278
telemt_upstream_connect_attempt_total 24434
telemt_upstream_connect_success_total 24038
telemt_upstream_connect_fail_total 396
telemt_upstream_connect_attempts_per_request{bucket="1"} 24434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7814
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 396
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 41175
telemt_me_reconnect_success_total 11720
telemt_me_reader_eof_total 12974
telemt_me_idle_close_by_peer_total 12974
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 164864
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 431397
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1138
telemt_desync_full_logged_total 287
telemt_desync_suppressed_total 851
telemt_desync_frames_bucket_total{bucket="1_2"} 304
telemt_desync_frames_bucket_total{bucket="3_10"} 467
telemt_desync_frames_bucket_total{bucket="gt_10"} 367
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12751
telemt_me_refill_failed_total 921
telemt_me_writer_restored_same_endpoint_total 11688
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1031
telemt_user_connections_total{user="hello"} 440978
telemt_user_connections_current{user="hello"} 693
telemt_user_octets_from_client{user="hello"} 8485219602 (7.90 GB)
telemt_user_octets_to_client{user="hello"} 158295413355 (147.42 GB)
telemt_user_msgs_from_client{user="hello"} 141315
telemt_user_msgs_to_client{user="hello"} 821588
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 52119.8 (14h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 634048
telemt_connections_bad_total 7689
telemt_handshake_timeouts_total 13262
telemt_upstream_connect_attempt_total 11656
telemt_upstream_connect_success_total 11595
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 11656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6263
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_reconnect_attempts_total 10038
telemt_me_reconnect_success_total 8995
telemt_me_reader_eof_total 9564
telemt_me_idle_close_by_peer_total 9564
telemt_me_route_drop_no_conn_total 157856
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 514420
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1996
telemt_desync_full_logged_total 660
telemt_desync_suppressed_total 1336
telemt_desync_frames_bucket_total{bucket="1_2"} 576
telemt_desync_frames_bucket_total{bucket="3_10"} 796
telemt_desync_frames_bucket_total{bucket="gt_10"} 624
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 9135
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 8987
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 514451
telemt_user_connections_current{user="hello"} 749
telemt_user_octets_from_client{user="hello"} 6638892736 (6.18 GB)
telemt_user_octets_to_client{user="hello"} 185218058540 (172.50 GB)
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 112
```