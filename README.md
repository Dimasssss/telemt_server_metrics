# Server Metrics 2026-03-13 23:35:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 149821.7 (41h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4574653
telemt_connections_bad_total 38388
telemt_handshake_timeouts_total 107745
telemt_upstream_connect_attempt_total 31496
telemt_upstream_connect_success_total 31281
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 31496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13956
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_timeout_total 6651
telemt_me_reconnect_attempts_total 31601
telemt_me_reconnect_success_total 21471
telemt_me_reader_eof_total 23030
telemt_me_idle_close_by_peer_total 23029
telemt_me_route_drop_no_conn_total 1729200
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4192115
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16601
telemt_desync_full_logged_total 4470
telemt_desync_suppressed_total 12131
telemt_desync_frames_bucket_total{bucket="1_2"} 4132
telemt_desync_frames_bucket_total{bucket="3_10"} 6351
telemt_desync_frames_bucket_total{bucket="gt_10"} 6118
telemt_pool_swap_total 127
telemt_me_writer_removed_unexpected_total 22099
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 21458
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 628
telemt_user_connections_total{user="hello"} 4194039
telemt_user_connections_current{user="hello"} 662
telemt_user_octets_from_client{user="hello"} 61787406144 (57.54 GB)
telemt_user_octets_to_client{user="hello"} 1326204303221 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 49485.4 (13h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 613881
telemt_connections_bad_total 45531
telemt_handshake_timeouts_total 12598
telemt_upstream_connect_attempt_total 13955
telemt_upstream_connect_success_total 13717
telemt_upstream_connect_fail_total 238
telemt_upstream_connect_attempts_per_request{bucket="1"} 13955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5633
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 238
telemt_me_keepalive_timeout_total 1924
telemt_me_reconnect_attempts_total 12658
telemt_me_reconnect_success_total 9220
telemt_me_reader_eof_total 9773
telemt_me_idle_close_by_peer_total 9772
telemt_me_route_drop_no_conn_total 221566
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 526757
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1643
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 712
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 9462
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 9212
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 242
telemt_user_connections_total{user="hello"} 528708
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 5806570601 (5.41 GB)
telemt_user_octets_to_client{user="hello"} 173052555312 (161.17 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 179442.1 (49h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3317659
telemt_connections_bad_total 32311
telemt_handshake_timeouts_total 221920
telemt_upstream_connect_attempt_total 39922
telemt_upstream_connect_success_total 39901
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 39922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20853
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18819
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10341
telemt_me_reconnect_attempts_total 35593
telemt_me_reconnect_success_total 30637
telemt_me_reader_eof_total 32523
telemt_me_idle_close_by_peer_total 32522
telemt_me_route_drop_no_conn_total 1138163
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2756453
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9026
telemt_desync_full_logged_total 3035
telemt_desync_suppressed_total 5991
telemt_desync_frames_bucket_total{bucket="1_2"} 1519
telemt_desync_frames_bucket_total{bucket="3_10"} 3269
telemt_desync_frames_bucket_total{bucket="gt_10"} 4238
telemt_pool_swap_total 167
telemt_me_writer_removed_unexpected_total 31087
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 30596
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 450
telemt_user_connections_total{user="hello"} 2755705
telemt_user_connections_current{user="hello"} 327
telemt_user_octets_from_client{user="hello"} 44761624680 (41.69 GB)
telemt_user_octets_to_client{user="hello"} 974787640053 (907.84 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 179444.7 (49h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2184743
telemt_connections_bad_total 22853
telemt_handshake_timeouts_total 230490
telemt_upstream_connect_attempt_total 55913
telemt_upstream_connect_success_total 53460
telemt_upstream_connect_fail_total 2316
telemt_upstream_connect_attempts_per_request{bucket="1"} 55639
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21259
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2315
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20351
telemt_me_reconnect_attempts_total 46514
telemt_me_reconnect_success_total 37492
telemt_me_reader_eof_total 40218
telemt_me_idle_close_by_peer_total 40211
telemt_me_route_drop_no_conn_total 761049
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1769706
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3796
telemt_desync_full_logged_total 1217
telemt_desync_suppressed_total 2579
telemt_desync_frames_bucket_total{bucket="1_2"} 1003
telemt_desync_frames_bucket_total{bucket="3_10"} 1587
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 157
telemt_me_writer_removed_unexpected_total 38097
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 37468
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 605
telemt_user_connections_total{user="hello"} 1775597
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 27348153299 (25.47 GB)
telemt_user_octets_to_client{user="hello"} 661394872954 (615.97 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 48878.0 (13h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 658198
telemt_connections_bad_total 7858
telemt_handshake_timeouts_total 7643
telemt_upstream_connect_attempt_total 11575
telemt_upstream_connect_success_total 11224
telemt_upstream_connect_fail_total 351
telemt_upstream_connect_attempts_per_request{bucket="1"} 11575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5796
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 351
telemt_me_keepalive_timeout_total 1444
telemt_me_reconnect_attempts_total 39530
telemt_me_reconnect_success_total 8752
telemt_me_reader_eof_total 9871
telemt_me_idle_close_by_peer_total 9870
telemt_me_route_drop_no_conn_total 249499
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 612962
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1611
telemt_desync_full_logged_total 507
telemt_desync_suppressed_total 1104
telemt_desync_frames_bucket_total{bucket="1_2"} 489
telemt_desync_frames_bucket_total{bucket="3_10"} 630
telemt_desync_frames_bucket_total{bucket="gt_10"} 492
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 9797
telemt_me_refill_failed_total 958
telemt_me_writer_restored_same_endpoint_total 8747
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1045
telemt_user_connections_total{user="hello"} 612861
telemt_user_connections_current{user="hello"} 253
telemt_user_octets_from_client{user="hello"} 9755206512 (9.09 GB)
telemt_user_octets_to_client{user="hello"} 200211318256 (186.46 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 27
```