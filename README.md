# Server Metrics 2026-03-15 14:35:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 58864.1 (16h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1829343
telemt_connections_bad_total 100708
telemt_handshake_timeouts_total 20582
telemt_upstream_connect_attempt_total 11753
telemt_upstream_connect_success_total 11704
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 11753
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5537
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 13630
telemt_me_reconnect_success_total 8739
telemt_me_reader_eof_total 9358
telemt_me_idle_close_by_peer_total 9358
telemt_me_route_drop_no_conn_total 626287
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1547553
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5859
telemt_desync_full_logged_total 1635
telemt_desync_suppressed_total 4224
telemt_desync_frames_bucket_total{bucket="1_2"} 1469
telemt_desync_frames_bucket_total{bucket="3_10"} 2266
telemt_desync_frames_bucket_total{bucket="gt_10"} 2124
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 9034
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 8728
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 295
telemt_user_connections_total{user="hello"} 1547154
telemt_user_connections_current{user="hello"} 2324
telemt_user_octets_from_client{user="hello"} 22017557768 (20.51 GB)
telemt_user_octets_to_client{user="hello"} 608467869008 (566.68 GB)
telemt_user_unique_ips_current{user="hello"} 669
telemt_user_unique_ips_recent_window{user="hello"} 297
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 58864.7 (16h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 742346
telemt_connections_bad_total 40083
telemt_handshake_timeouts_total 58024
telemt_upstream_connect_attempt_total 14962
telemt_upstream_connect_success_total 14889
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 14962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6787
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 11679
telemt_me_reconnect_success_total 11584
telemt_me_reader_eof_total 12246
telemt_me_idle_close_by_peer_total 12246
telemt_me_route_drop_no_conn_total 184855
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 558801
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1992
telemt_desync_full_logged_total 688
telemt_desync_suppressed_total 1304
telemt_desync_frames_bucket_total{bucket="1_2"} 739
telemt_desync_frames_bucket_total{bucket="3_10"} 729
telemt_desync_frames_bucket_total{bucket="gt_10"} 524
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 11727
telemt_me_writer_restored_same_endpoint_total 11572
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 559052
telemt_user_connections_current{user="hello"} 746
telemt_user_octets_from_client{user="hello"} 7820797367 (7.28 GB)
telemt_user_octets_to_client{user="hello"} 210697546884 (196.23 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 58864.7 (16h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1591853
telemt_connections_bad_total 46231
telemt_handshake_timeouts_total 163464
telemt_upstream_connect_attempt_total 12954
telemt_upstream_connect_success_total 12893
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 12954
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6163
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 11164
telemt_me_reconnect_success_total 9910
telemt_me_reader_eof_total 10502
telemt_me_idle_close_by_peer_total 10502
telemt_me_route_drop_no_conn_total 434936
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 987002
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2482
telemt_desync_full_logged_total 915
telemt_desync_suppressed_total 1567
telemt_desync_frames_bucket_total{bucket="1_2"} 571
telemt_desync_frames_bucket_total{bucket="3_10"} 952
telemt_desync_frames_bucket_total{bucket="gt_10"} 959
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10081
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 9891
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 983091
telemt_user_connections_current{user="hello"} 1378
telemt_user_octets_from_client{user="hello"} 14186829740 (13.21 GB)
telemt_user_octets_to_client{user="hello"} 354325868100 (329.99 GB)
telemt_user_unique_ips_current{user="hello"} 412
telemt_user_unique_ips_recent_window{user="hello"} 192
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 58864.6 (16h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 769984
telemt_connections_bad_total 72644
telemt_handshake_timeouts_total 40255
telemt_upstream_connect_attempt_total 153325
telemt_upstream_connect_success_total 152840
telemt_upstream_connect_fail_total 485
telemt_upstream_connect_attempts_per_request{bucket="1"} 153325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 141036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11778
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 485
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 52227
telemt_me_reconnect_success_total 11794
telemt_me_reader_eof_total 13389
telemt_me_idle_close_by_peer_total 13389
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 171233
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 448648
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1175
telemt_desync_full_logged_total 299
telemt_desync_suppressed_total 876
telemt_desync_frames_bucket_total{bucket="1_2"} 324
telemt_desync_frames_bucket_total{bucket="3_10"} 476
telemt_desync_frames_bucket_total{bucket="gt_10"} 375
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 13169
telemt_me_refill_failed_total 1265
telemt_me_writer_restored_same_endpoint_total 11762
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1375
telemt_user_connections_total{user="hello"} 586600
telemt_user_connections_current{user="hello"} 919
telemt_user_octets_from_client{user="hello"} 11043710760 (10.29 GB)
telemt_user_octets_to_client{user="hello"} 198365150334 (184.74 GB)
telemt_user_msgs_from_client{user="hello"} 2718116
telemt_user_msgs_to_client{user="hello"} 9943090
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 58865.5 (16h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 786272
telemt_connections_bad_total 9295
telemt_handshake_timeouts_total 16363
telemt_upstream_connect_attempt_total 13003
telemt_upstream_connect_success_total 12932
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 13003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6953
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 13646
telemt_me_reconnect_success_total 9966
telemt_me_reader_eof_total 10655
telemt_me_idle_close_by_peer_total 10655
telemt_me_route_drop_no_conn_total 195434
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 640790
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2313
telemt_desync_full_logged_total 777
telemt_desync_suppressed_total 1536
telemt_desync_frames_bucket_total{bucket="1_2"} 697
telemt_desync_frames_bucket_total{bucket="3_10"} 894
telemt_desync_frames_bucket_total{bucket="gt_10"} 722
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 10198
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 9958
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 232
telemt_user_connections_total{user="hello"} 640834
telemt_user_connections_current{user="hello"} 948
telemt_user_octets_from_client{user="hello"} 8030948608 (7.48 GB)
telemt_user_octets_to_client{user="hello"} 239324834108 (222.89 GB)
telemt_user_unique_ips_current{user="hello"} 248
telemt_user_unique_ips_recent_window{user="hello"} 122
```