# Server Metrics 2026-03-11 08:49:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 66122.1 (18h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1379095
telemt_connections_bad_total 15747
telemt_handshake_timeouts_total 40160
telemt_upstream_connect_attempt_total 13765
telemt_upstream_connect_success_total 13756
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 13765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6734
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 755
telemt_me_reconnect_attempts_total 22094
telemt_me_reconnect_success_total 10408
telemt_me_reader_eof_total 11274
telemt_me_idle_close_by_peer_total 11274
telemt_me_route_drop_no_conn_total 506979
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1249666
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6141
telemt_desync_full_logged_total 1702
telemt_desync_suppressed_total 4439
telemt_desync_frames_bucket_total{bucket="1_2"} 1618
telemt_desync_frames_bucket_total{bucket="3_10"} 2334
telemt_desync_frames_bucket_total{bucket="gt_10"} 2189
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10873
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 10402
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 465
telemt_user_connections_total{user="hello"} 1249339
telemt_user_connections_current{user="hello"} 1307
telemt_user_octets_from_client{user="hello"} 16617532256 (15.48 GB)
telemt_user_octets_to_client{user="hello"} 361502865200 (336.68 GB)
telemt_user_unique_ips_current{user="hello"} 366
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 66178.7 (18h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 533233
telemt_connections_bad_total 9034
telemt_handshake_timeouts_total 29526
telemt_upstream_connect_attempt_total 22727
telemt_upstream_connect_success_total 19801
telemt_upstream_connect_fail_total 2926
telemt_upstream_connect_attempts_per_request{bucket="1"} 22727
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8987
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8571
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2926
telemt_me_keepalive_timeout_total 2061
telemt_me_reconnect_attempts_total 14371
telemt_me_reconnect_success_total 13539
telemt_me_reader_eof_total 14328
telemt_me_idle_close_by_peer_total 14326
telemt_me_route_drop_no_conn_total 224716
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 451393
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2137
telemt_desync_full_logged_total 655
telemt_desync_suppressed_total 1482
telemt_desync_frames_bucket_total{bucket="1_2"} 709
telemt_desync_frames_bucket_total{bucket="3_10"} 770
telemt_desync_frames_bucket_total{bucket="gt_10"} 658
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 13697
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 13517
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 453633
telemt_user_connections_current{user="hello"} 475
telemt_user_octets_from_client{user="hello"} 4405435534 (4.10 GB)
telemt_user_octets_to_client{user="hello"} 121031681212 (112.72 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 66178.6 (18h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 915272
telemt_connections_bad_total 7239
telemt_handshake_timeouts_total 74864
telemt_upstream_connect_attempt_total 17870
telemt_upstream_connect_success_total 17651
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 17870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7945
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_keepalive_timeout_total 756
telemt_me_reconnect_attempts_total 25621
telemt_me_reconnect_success_total 13260
telemt_me_reader_eof_total 14268
telemt_me_idle_close_by_peer_total 14268
telemt_me_route_drop_no_conn_total 302666
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 795541
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2278
telemt_desync_full_logged_total 676
telemt_desync_suppressed_total 1602
telemt_desync_frames_bucket_total{bucket="1_2"} 547
telemt_desync_frames_bucket_total{bucket="3_10"} 829
telemt_desync_frames_bucket_total{bucket="gt_10"} 902
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 13813
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 13249
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 553
telemt_user_connections_total{user="hello"} 796351
telemt_user_connections_current{user="hello"} 757
telemt_user_octets_from_client{user="hello"} 9443959857 (8.80 GB)
telemt_user_octets_to_client{user="hello"} 240332048345 (223.83 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 66178.9 (18h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 680312
telemt_connections_bad_total 61922
telemt_handshake_timeouts_total 66458
telemt_upstream_connect_attempt_total 18311
telemt_upstream_connect_success_total 18311
telemt_upstream_connect_attempts_per_request{bucket="1"} 18311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8110
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 691
telemt_me_reconnect_attempts_total 16054
telemt_me_reconnect_success_total 15001
telemt_me_reader_eof_total 15938
telemt_me_idle_close_by_peer_total 15937
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 211339
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 530546
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1236
telemt_desync_full_logged_total 465
telemt_desync_suppressed_total 771
telemt_desync_frames_bucket_total{bucket="1_2"} 410
telemt_desync_frames_bucket_total{bucket="3_10"} 469
telemt_desync_frames_bucket_total{bucket="gt_10"} 357
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 15178
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 14979
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 529921
telemt_user_connections_current{user="hello"} 475
telemt_user_octets_from_client{user="hello"} 6233411056 (5.81 GB)
telemt_user_octets_to_client{user="hello"} 148945340228 (138.72 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 66178.8 (18h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 717801
telemt_connections_bad_total 5982
telemt_handshake_timeouts_total 6746
telemt_upstream_connect_attempt_total 18154
telemt_upstream_connect_success_total 18081
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 18154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8613
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 733
telemt_me_reconnect_attempts_total 18446
telemt_me_reconnect_success_total 14655
telemt_me_reader_eof_total 15494
telemt_me_idle_close_by_peer_total 15494
telemt_me_route_drop_no_conn_total 242052
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 651464
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2848
telemt_desync_full_logged_total 1076
telemt_desync_suppressed_total 1772
telemt_desync_frames_bucket_total{bucket="1_2"} 997
telemt_desync_frames_bucket_total{bucket="3_10"} 1186
telemt_desync_frames_bucket_total{bucket="gt_10"} 665
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 14959
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 14655
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 304
telemt_user_connections_total{user="hello"} 651152
telemt_user_connections_current{user="hello"} 654
telemt_user_octets_from_client{user="hello"} 10564480283 (9.84 GB)
telemt_user_octets_to_client{user="hello"} 235105888410 (218.96 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 129
```