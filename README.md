# Server Metrics 2026-03-15 18:05:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 71434.2 (19h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2540365
telemt_connections_bad_total 150842
telemt_handshake_timeouts_total 33182
telemt_upstream_connect_attempt_total 13849
telemt_upstream_connect_success_total 13790
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 13849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6568
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 15106
telemt_me_reconnect_success_total 10208
telemt_me_reader_eof_total 10911
telemt_me_idle_close_by_peer_total 10911
telemt_me_route_drop_no_conn_total 879110
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2119829
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8235
telemt_desync_full_logged_total 2247
telemt_desync_suppressed_total 5988
telemt_desync_frames_bucket_total{bucket="1_2"} 2030
telemt_desync_frames_bucket_total{bucket="3_10"} 3143
telemt_desync_frames_bucket_total{bucket="gt_10"} 3062
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 10532
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 10197
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 324
telemt_user_connections_total{user="hello"} 2119300
telemt_user_connections_current{user="hello"} 2579
telemt_user_octets_from_client{user="hello"} 31719279416 (29.54 GB)
telemt_user_octets_to_client{user="hello"} 806761463160 (751.36 GB)
telemt_user_unique_ips_current{user="hello"} 718
telemt_user_unique_ips_recent_window{user="hello"} 294
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 71434.8 (19h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 983295
telemt_connections_bad_total 55734
telemt_handshake_timeouts_total 63158
telemt_upstream_connect_attempt_total 17796
telemt_upstream_connect_success_total 17700
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 17796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8135
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 14968
telemt_me_reconnect_success_total 13757
telemt_me_reader_eof_total 14557
telemt_me_idle_close_by_peer_total 14557
telemt_me_route_drop_no_conn_total 254734
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 759378
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2219
telemt_desync_full_logged_total 750
telemt_desync_suppressed_total 1469
telemt_desync_frames_bucket_total{bucket="1_2"} 778
telemt_desync_frames_bucket_total{bucket="3_10"} 836
telemt_desync_frames_bucket_total{bucket="gt_10"} 605
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 13973
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 13745
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 759607
telemt_user_connections_current{user="hello"} 881
telemt_user_octets_from_client{user="hello"} 11025008839 (10.27 GB)
telemt_user_octets_to_client{user="hello"} 285386725984 (265.79 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 71434.5 (19h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2166274
telemt_connections_bad_total 50599
telemt_handshake_timeouts_total 214919
telemt_upstream_connect_attempt_total 15392
telemt_upstream_connect_success_total 15315
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 15392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7326
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 12970
telemt_me_reconnect_success_total 11701
telemt_me_reader_eof_total 12398
telemt_me_idle_close_by_peer_total 12398
telemt_me_route_drop_no_conn_total 562768
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1351892
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3519
telemt_desync_full_logged_total 1265
telemt_desync_suppressed_total 2254
telemt_desync_frames_bucket_total{bucket="1_2"} 801
telemt_desync_frames_bucket_total{bucket="3_10"} 1369
telemt_desync_frames_bucket_total{bucket="gt_10"} 1349
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 11906
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11682
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 1347777
telemt_user_connections_current{user="hello"} 1505
telemt_user_octets_from_client{user="hello"} 25095305176 (23.37 GB)
telemt_user_octets_to_client{user="hello"} 501021198172 (466.61 GB)
telemt_user_unique_ips_current{user="hello"} 452
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 71434.6 (19h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1046728
telemt_connections_bad_total 82061
telemt_handshake_timeouts_total 51185
telemt_upstream_connect_attempt_total 170787
telemt_upstream_connect_success_total 170187
telemt_upstream_connect_fail_total 600
telemt_upstream_connect_attempts_per_request{bucket="1"} 170787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 156810
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13317
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 600
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 61698
telemt_me_reconnect_success_total 13633
telemt_me_reader_eof_total 15499
telemt_me_idle_close_by_peer_total 15499
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 248711
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 662366
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 44
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1851
telemt_desync_full_logged_total 506
telemt_desync_suppressed_total 1345
telemt_desync_frames_bucket_total{bucket="1_2"} 476
telemt_desync_frames_bucket_total{bucket="3_10"} 715
telemt_desync_frames_bucket_total{bucket="gt_10"} 660
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 15279
telemt_me_refill_failed_total 1504
telemt_me_writer_restored_same_endpoint_total 13597
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1646
telemt_user_connections_total{user="hello"} 814879
telemt_user_connections_current{user="hello"} 866
telemt_user_octets_from_client{user="hello"} 15195152385 (14.15 GB)
telemt_user_octets_to_client{user="hello"} 290481399200 (270.53 GB)
telemt_user_msgs_from_client{user="hello"} 3035962
telemt_user_msgs_to_client{user="hello"} 10927629
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 71435.7 (19h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1060600
telemt_connections_bad_total 12592
telemt_handshake_timeouts_total 23313
telemt_upstream_connect_attempt_total 15708
telemt_upstream_connect_success_total 15624
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 15708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8367
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 15727
telemt_me_reconnect_success_total 12032
telemt_me_reader_eof_total 12834
telemt_me_idle_close_by_peer_total 12834
telemt_me_route_drop_no_conn_total 264968
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 879062
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3016
telemt_desync_full_logged_total 1008
telemt_desync_suppressed_total 2008
telemt_desync_frames_bucket_total{bucket="1_2"} 924
telemt_desync_frames_bucket_total{bucket="3_10"} 1115
telemt_desync_frames_bucket_total{bucket="gt_10"} 977
telemt_pool_swap_total 60
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 12291
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 12024
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 879085
telemt_user_connections_current{user="hello"} 1063
telemt_user_octets_from_client{user="hello"} 10922879956 (10.17 GB)
telemt_user_octets_to_client{user="hello"} 308765370136 (287.56 GB)
telemt_user_unique_ips_current{user="hello"} 267
telemt_user_unique_ips_recent_window{user="hello"} 130
```